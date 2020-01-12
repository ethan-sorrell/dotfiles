# dotfiles

# Notes
- libinput > synaptics for touchpad

# Rough Walkthrough
```
su
adduser <user-name> sudo
```
re-log
```
sudo apt install rxvt-unicode emacs i3 rofi neovim fish calibre rclone redshift-gtk curl tmux
```
on laptop also do
```
apt install xbacklight
```
make fish default shell
```
chsh -s /usr/bin/fish
```
hard link dotfiles
rename appropriate i3 config file
```
mv .config/i3/laptop-config config
```
install vim-plug
https://github.com/junegunn/vim-plug
