# Tokyonight gnome shell

To setup gnome shell:

1. `git clone https://github.com/kerry-vorticity/tokyonight.git`
2. `cd tokyonight`
3. `sudo cp -r Tokyonight-Dark-BL /usr/share/themes`
4. `sudo apt-get install gnome-tweaks`
5. `sudo apt-get install gnome-shell-extensions`
6. `sudo reboot`
7. Go to Applications -> Open 'Extensions' -> Turn on 'user-themes'
8. Run `gnome-tweaks` in terminal
9. Go to the appearance tab and change eligible themes to Tokyonight Dark-BL

To setup gnome terminal:

1. `dconf load /org/gnome/terminal/ < ~/.config/nvim/tokyonight-gnome-terminal.txt`
2. Go to Terminal -> 'Preferences' at the top of the desktop and right click Tokyonight-Moon and set as default
