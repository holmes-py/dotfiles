# dotfiles
A dump to contain my i3 dotfiles with polybar. Combined with my tmux config, these are supposed to be in HackTheBox color scheme.   
For reference, adding screenshot:
![image](https://user-images.githubusercontent.com/54495695/216639472-0c53690c-5296-43cc-8702-1c142f1551b4.png)


# For Debian Based Users-

```
sudo apt install i3-gaps alacritty polybar rofi dmenu picom dunst
git clone https://github.com/holmes-py/dotfiles
cd dotfiles; cp * ~/.config; cd ~/.config
cd i3; chmod +x *.sh; cd ../polybar; chmod +x *.sh
reboot
```

# For Arch Based Users- 

```
yay -S i3-gaps alacritty polybar rofi picom dunst dmenu
git clone https://github.com/holmes-py/dotfiles
cd dotfiles; cp * ~/.config; cd ~/.config
cd i3; chmod +x *.sh; cd ../polybar; chmod +x *.sh
reboot
```
