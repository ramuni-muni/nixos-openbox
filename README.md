# nixos-openbox
nixos configuration include openbox ricing as GUI

how to install:

download and put file configuration.nix to /etc/nixos replace the original configuration.nix

edit, change the storage device id with your storage device id. this configuration use MBR bootloader. if you use efi read the wiki from nixos.org how to configure it.

this configuration use fbdev video driver, i think all device can use it but not optimized. change or edit the video driver if you want use GPU.

change the user name as you like.

rebuild your nixos with command:

  sudo nixos-rebuild boot
  
then reboot.
