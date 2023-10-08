# Vestia Zeta - Hololive Indonesia
Vestia Zeta Grub Pack


## Donate Dulu Cui Buat Beli Kopi
Donate Me :
Seabank - 9018 9656 6446


## HOW TO INSTALL
1. Download and unzip file (2 File in Vestia Zeta Grub Theme : 1.Vestia-Zeta & 2.Vestia-Zeta-v2)
    - cd Downloads/
    - git clone https://github.com/WallnutPG/VestiaZeta-GrubThemes.git
    - extract file

3. Copy file into grub themes directory
    example copy :
    - copy file Vestia-Zeta to directory (/usr/share/grub/themes)
    example command :
    - sudo cp -r Vestia-Zeta  /usr/share/grub/themes

4. Edit grub file
    sudo nano /etc/default/grub

5. Add the theme to the bottom of the text file
    GRUB_THEME="/usr/share/grub/themes/Vestia-Zeta/theme.txt"

6. Update Grub
    sudo grub-mkconfig -o /boot/grub/grub.cfg

7. Reboot the computer

## PREVIEW
![Vestia-Zeta](/preview/vestia-zeta.png)
![Vestia-Zeta-v2](/preview/vestia-zeta-v2.png)

## Created By :
github.com/WallnutPG
