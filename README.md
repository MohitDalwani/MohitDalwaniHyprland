
Здесь находится мои конфиги для Hyprland и других полезных штук, дополняющих его. 

Вот что я использую:

OS: Arch Linux 
Shell: Fish 
Terminal: Kitty 
File Manager: Thunar 

Непосредственно для дополнения Hyprland: 

waybar - полоса вверху экрана с полезной информацией 
wofi - поиск по установленным приложения 
mako - более красивые уведомления 
fastfetch - мини neofetch при каждом запуске терминала
nwg-look - для смены иконок 
hyprpaper - обои для Hyrpland
hyprlock - лок экрана на SUPER + L
hyprshot - делать скриншоты с помощью Prt Scr 
wlogout - меню, позволяющее выключить, перезагрузить систему и т.п. 

Так же тут я оставлю свой пак обоев для Hyprpaper.

Использую следующие шрифты: 
ttf-font-awesome 
otf-font-awesome 
ttf-jetbrains-mono

Как это выглядит:

![[2025-05-23-223352_hyprshot.png]]

Или так:

![[2025-05-23-231354_hyprshot.png]]

как выглядит wlogout:

![[2025-05-24-225911_hyprshot.png]]

Вот так теперь выглядят уведомления:

![[2025-05-24-225933_hyprshot.png]]

Для справки: 

Смена на fish: 

sudo pacman -S fish pkgfile ttf-dejavu powerline-fonts inetutils
chsh fish
/bin/fish

*papirus-icon-theme fastfetch (иконки)*

[https://github.com/vinceliuice/Graphite-gtk-theme](https://github.com/vinceliuice/Graphite-gtk-theme)

./install.sh

*wlogout*

[https://github.com/ArtsyMacaw/wlogout.git](https://github.com/ArtsyMacaw/wlogout.git)

cd wlogout 
meson build 
ninja -C build 
sudo ninja -C build install

yay -S hyprshot

все конфиги уже прописаны, нужно только скопировать в папку .config/

установить hyprshot через yay: 
yay -S hyprshot