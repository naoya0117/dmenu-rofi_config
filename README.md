# dmenu-rofi_config
## 使い方
- dmenuの見た目に極力近づけ、j4-make-configのgreenish themeに合うようにrofiの出力を変更しました。
- rofiをインストールする
```
$ sudo pacman -S rofi
```
- i3の設定ファイルで、rofiを利用するよう変更する。(dmenu_runの行をコメントアウトし、```bindcode $mod+40 exec "rofi -show"```を追加する)
```
$ git clone https://www.github.com/naoya0117/dmenu-rofi_config.git ~/.config/rofi
```
