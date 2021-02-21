# My gentoo dotfiles

![](https://github.com/maksmeshkov/dotfiles/blob/dracula/screenshots/dracula_stacked.png)

---

## Apps list

-   `zathura` - pdf/ebooks
-   `nvim` - text editor
    -   `coc.nvim` - extension manager for nvim
-   `Fira Mono patched for Powerline` - font for urxvt
-   `kochi` - japanese font
-   `arc` - icon theme
-   `chromium` - web browser
-   `bluez` - manage bluetooth devices
-   `urxvt` - terminal
-   `ranger` - curses filemanager (install w3m image preview. flags are in package.use)
-   `redshift` - ease bluelight strain on your eyes
-   `moc` - terminal music player
-   `fish` - cool shell
-   `maim` - screenshooter
-   `doas` - alternative to sudo without bloat
-   `wacom`-utility - to manage wacom tablet (uncomment exec line in i3/conf)
-   `dmenu` - minimalistic app launcher
-   `qbittorrent` - torrent client
-   `picom` - compositor
-   `nvtop` - htop for Nvidia GPU
-   [`gentoo-lto`](https://github.com/InBetweenNames/gentooLTO) - use to optimize compiled programs

---

-   `yay` - aur packet manager
-   `arandr` - GUI for xrandr
-   `lxappearance` - set gkt theme
-   `linux zen` - kernel (don't forget to install dkms hooks for nvidia)
-   `thunar` (and plugins) - GUI file manager
-   `pywal` - colorscheme setter
-   `nerd` fonts complete - every font in one place (and icons!)

## Notes

-   To use dbus for spotify, chromium, playerctl and whatever, launch WM
    session with dbus, so that all WM children will be children of dbus. Put
    `exec dbus-launch --exit-with-session bspwm` in your `.xinitrc`
