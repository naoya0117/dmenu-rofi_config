# dmenu-rofi_config
- dmenuの見た目に極力近づけ、j4-make-configのgreenish themeに合うようにrofiの出力を変更しました。
## 使い方
- rofiをインストールする
```
$ sudo pacman -S rofi
```
- i3のconfigファイルで、rofiを利用するよう変更する。(configのdmenu_runの行をコメントアウトし、```bindcode $mod+40 exec "rofi -show"```を追加する)
```
$ git clone https://www.github.com/naoya0117/dmenu-rofi_config.git ~/.config/rofi
```
