# theme-polybar-macstyle

## Preview

## Clean
![clean](/preview/ArchLabs.png)
<br />
## Menu
![Menu](/preview/ArchLabs1.png)
Relevant files: [.config/rofi/rofimenu.config](.config/rofi/rofimenu.config)

Relevant files: [.config/rofi/rofiscript.sh](.config/rofi/rofiscript.sh)

Relevant files: [.config/rofi/sidemenu2.rasi](.config/rofi/sidemenu2.rasi)
<br />
## Control_Center
![Control_Center](/preview/ArchLabs2.png)
Relevant files: [.config/polybar/dropdown/polybar_modules/tablet_options](.config/polybar/dropdown/polybar_modules/tablet_options)

Relevant files: [.config/polybar/dropdown/polybar_tablet](.config/polybar/dropdown/polybar_tablet)


* Distro: [ArchLabs](https://archlabslinux.com/)
* Window manager: [i3-gaps](https://github.com/Airblader/i3)
* Bar: [Polybar](https://github.com/polybar/polybar)
* Launcher: [Rofi](https://github.com/davatorium/rofi)
* Compositor [picom (kawase-blur)](https://github.com/ibhagwan/picom)

### Other prerequisites
* `mpc mpd ncmpcpp`
* `xdotool`
* `imagemagick`
* `nitrogen`
* `pamac`
* `scrot`
* `pavucontrol`
* `ttf-font-awesome` (AUR)
* `Sans` (or change the font to whatever you want)
* `Iosevka Nerd Font`


### add this 2 lines to your i3 config

exec_always --no-startup-id ~/.config/polybar/dropdown/tablet_mode

bindsym $mod+BackSpace exec --no-startup-id ~/.config/polybar/dropdown/polybar_modules/tablet_options toggle


