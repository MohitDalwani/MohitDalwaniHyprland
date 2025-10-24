
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

![2025-05-23-223352_hyprshot](https://github.com/user-attachments/assets/56124db1-528c-468b-ab8c-cbc1acf8d57c)

Или так:

![2025-05-23-231354_hyprshot](https://github.com/user-attachments/assets/43eb8900-12d3-46cc-957d-0fc985231e92)

<img width="1920" height="1080" alt="hyprland" src="https://github.com/user-attachments/assets/12b415a8-6e47-4d82-a6c3-877128db3247" />

<img width="1921" height="1081" alt="2025-10-23-192849_hyprshot" src="https://github.com/user-attachments/assets/5d949e31-7e22-4905-b52b-2dc5cae6876c" />

как выглядит wlogout:

![2025-05-24-225911_hyprshot](https://github.com/user-attachments/assets/28d4c59b-b50f-44ff-b312-0923f9a586be)

Вот так теперь выглядят уведомления:

![2025-05-24-225933_hyprshot](https://github.com/user-attachments/assets/3be53b38-1b27-4c36-b334-a13f8eaba476)

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

Шрифты: sudo pacman -S ttf-font-awesome otf-font-awesome ttf-jetbrains-mono

все конфиги уже прописаны, нужно только скопировать в папку .config/

установить hyprshot через yay: 
yay -S hyprshot
