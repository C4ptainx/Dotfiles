# Dotfiles
Esta es mi configuracion del entonro de Antonio Sarosi 

#Qtile
El entorno de qtile es de Antonio Sarosi, https://github.com/antoniosarosi/dotfiles en su repositorio podemos encontrar la guia de instalacion, igualmente la instalacion de archlinux

Vamos a instalar paru en nuestro sistema para tener mayor acceso a paquetes
git clone https://aur.archlinux.org/paru.git 
cd paru
makepkg -si 

#Rofi 
sudo pacman -S rofi 

#Rofi-powermenu
Vamos a clonar este repositorio para tener las opciones de apgar, reiniciar, suspender, bloquear.

#Bloqueo de pantalla
Para tener un bloqueo de pantalla, vamos a instalar betterlockscreen 
paru -S betterlockscreen

#lightdm
vamos a instalar lightdm, pero con un tema de archlinux que es lightdm-webkit-theme-aether

sudo paru -S lightdm lightdm-webkit-theme-aether
sudo systemctl enable lightdm.service

#Zsh 
instalaremos zsh con powerlevel10k 
primero vamos a instalar zsh 
sudo pacman -S zsh
vamos a clonar el repositorio de powerlevel10k https://github.com/romkatv/powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc

poner touchpad 
en etc/X11/xorg.conf.d

instalar 
pulseaudio, blachlight, synaptics 



