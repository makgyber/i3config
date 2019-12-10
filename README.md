# i3config

Personal configuration for i3 window manager running in Manjaro Linux

Notes:
- locale needs to be en_US for dmenu to work
- run nitrogen in terminal to select background
- add nouveau.modeset=0 to grub/config then update-grub
- set lan IP to 192.168.0.225 for NAS access
- move 50-atmel-dfu.rules to /etc/udev/rules.d/
- groups should be: 
`sys bumblebee network power uucp lp wheel autologin jon`
- copy morc_menu to ./config/morc_menu/
- for trackpad natural scrolling, copy 30-touchpad.conf to /etc/X11/xorg.conf.d/
- install qmk build tools:
`sudo pacman -S base-devel gcc unzip wget zip avr-gcc avr-binutils avr-libc dfu-util arm-none-eabi-gcc arm-none-eabi-binutils arm-none-eabi-newlib git dfu-programmer dfu-util`
- set up git account
`
git config --global user.email "makgyber@gmail.com"
git config --global user.name "jon mereria"
`
