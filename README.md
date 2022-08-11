# polybar-bluetooth

Based on [polybar/polybar-scripts/system-bluetooth-bluetoothctl](https://github.com/polybar/polybar-scripts/blob/master/polybar-scripts/system-bluetooth-bluetoothctl) which broke and this is my fix

## dependencies

- bluetoothctl
- nerdfonts

## module
```
[module/bt]
type = custom/script
exec = $HOME/.config/scripts/polybar-bluetooth.sh
tail = true
click-left = $HOME/.config/scripts/polybar-bluetooth.sh --toggle &
```
