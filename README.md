<h1 align="center">Nord Theme Lain</h1>
<h4 align="center">Config files for i3wm</h4>
<p align="center">
<img src="https://64.media.tumblr.com/avatar_d7426ae460b6_128.pnj">
</p>
<p align="center">
<a href="#installation">Installation</a><br>
<a href="#dependencies">Dependencies & Fonts</a><br>
<a href="#shortcuts">Shortcuts</a><br>
</p>

<p align="center">
<h2>Preview i3wm, Polybar, Alacritty</h2>
  <img src="screenshot1.gif">
  <img src="screenshot2.gif">
<h2>Preview Rofi (dmenu & power-menu)</h2>
  <img src="screenshot3.gif">
</p>

<a name="installation"></a>
<h1 align="center">Installation</h1>

- Clone the repo

  ```
  git clone https://github.com/monte0x00/dotfiles-i3wm-nord-lain.git
  ```

- Open the file and copy the configurations folders to **~/.config** folder

  ```
  cd dotfiles-i3wm-nord-lain
  ```

  ```
  sudo cp -r alacritty i3 polybar rofi ~/.config
  ```

- Install Lain Wallpaper (we may have to create a backgrounds folder)

  ```
  cd dotfiles-i3wm-nord-lain
  ```

  ```
  sudo mkdir /usr/share/backgrounds
  ```

  ```
  sudo cp -r lain.jpg /usr/share/backgrounds
  ```

<a name="dependencies"></a>
<h1 align="center">Dependencies & Fonts</h1>
<h4>Dependencies can be Easily Installed from Terminal</h4>

| ***Dependencies***                   |
| -----                                |
| alacritty                            |
| xrandr                               |
| thunar                               |
| feh                                  |
| rofi                                 |
| polybar                              |
| xclip                                |
| maim                                 |

| ***Fonts***                          |
| -----                                |
| Cascadia Code                        |
| Symbols Nerd Font                    |


<a name="shortcuts"></a>
<h2>Shortcuts</h2>

| ***Key***                            | ***Action***               |
| -----                                | -----                      |
| ***Software***                       | ***Action***               |
| Super + t                            | alacritty                  |
| Super + a                            | rofi -show drun            |
| Super + Shift + q                    | rofi -show power-menu      |
| Super + e                            | thunar                     |
| Print                                | maim, xclip                |
| -----                                | -----                      |
| ***i3wm***                           | ***Action***               |
| Super + q                            | kill focused window        |
| Super + Left, Down, Up, Right        | toggle window focus        |
| Super + Shift + Left,Down,Up,Right   | move focused window        |
| Super + Space                        | toggle floating/tiling     |
| Super + f                            | toggle fullscreen          |
| Super + 1,2,3,4,5,6,7,8,9,0          | focus desktop 1-9          |
| Super + Shift + 1,2,3,4,5,6,7,8,9,0  | move window to desktop 1-9 |
| Super + Shift + r                    | restart i3wm               |
