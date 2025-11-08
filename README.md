# My Arch Linux Dotfiles

## Contains:
- Hyprland config
- Waybar config  
- Kitty terminal
- Wofi menu
- Fcitx5 input
- Fastfetch
- And other app configs

## Restore:
```bash
git clone https://github.com/SviridovSergey/dotfiles.git
cp -r dotfiles/.config ~/
cp dotfiles/.bashrc ~/
sudo pacman -S - < dotfiles/packages-list.txt
