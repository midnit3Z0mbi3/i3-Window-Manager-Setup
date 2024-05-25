# i3-Tiling-Window-Manager-Setup
<br>
<div align="center">
  <img src="https://y.yarn.co/c6abfd33-9330-4617-ba5a-436b34fdcf96_text.gif" alt="prometheus movie gif" width="50%"> 
</div>
<br><br>

**Install:**

Install 
<a href="https://www.debian.org/download">Debian</a> or 
<a href="https://www.kali.org/get-kali/#kali-platforms">Kali Linux</a>. Do not install a desktop environment.

update and upgrade

chmod +x *.sh

sudo bash i3_install_setup.sh

reboot

bash i3_customized.sh

Reload the configuration file and open lxapperance

sudo nano /etc/lightdm/lightdm-gtk-greeter.conf

reboot
<br>
<div align="center">
  <img src="debian_i3_thunar.png" alt="debian i3 desktop displaying dracula color theme. terminal and thunar." width="65%"> 
  <img src="debian_i3_cava_thunar.png" alt="debian i3 desktop displaying dracula color theme. thunar and cava." width="65%"> 
</div>
<br><br>

**Login Screen/Lightdm:**

edit the /etc/lightdm/lightdm-gtk-greeter.conf file to change the background of the login screen.

background= hex color code or path to image

userbackground= false (to use a solid color for the background)

userbackground= true (to use an image for the background)

font= monospace (you can place any font you want here)

If you would like the login page the same color as the desktop wallpaper, use hex code #1e1e2e

other <a href="https://www.color-name.com/neutral-blue.color">neutral colors</a> 

sudo nano /etc/lightdm/lightdm-gtk-greeter.conf

reboot

**Wallpaper:**

edit i3 config options at the bottom of the configuration file

image - feh

solid color (hex code) - xsetroot

other 
<a href="https://www.color-name.com/neutral-blue.color">neutral colors</a> 

wallpaper hd, 4k, 8k

https://pixlr.com

https://wall.alphacoders.com/

https://hdqwalls.com/

**Btop is installed. Btop is a terminal based resource monitor**

<br>
<div align="center">
  <img src="https://github.com/aristocratos/btop/blob/main/Img/normal.png" alt="gotop demo" width="65%">
</div>
<br>

**Key Bindings:**

Web Browser mod+b

File Manager mod+Shift+Return  

Password Manager mod+p  

Lock screen mod+x 

