# GRUB Themes

## Anime

<img src="anime/screenshot.png" />

### Install Instructions for Ubuntu

1. Download the [tar file](anime/anime.tar.xz)
2. Extract the file
3. Copy the contents to /boot/grub/themes/
4. Edit /etc/default/grub by adding
```bash
GRUB_THEME=/boot/grub/themes/anime/theme.txt
```
5. Update GRUB
```bash
sudo udpate-grub
```
6. Reboot and see your new GRUB menu

### Customise
Open design.svg to make any changes to the text and export as png.  
The 'Booting' text is stored in style.txt  