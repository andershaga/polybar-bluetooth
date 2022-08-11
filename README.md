# polybar-bluetooth

Based on [polybar/polybar-scripts/system-bluetooth-bluetoothctl](https://github.com/polybar/polybar-scripts/blob/master/polybar-scripts/system-bluetooth-bluetoothctl) it broke and this is my attempt to fix it_

```
[module/bt]
type = custom/script
exec = $HOME/.config/scripts/polybar-bluetooth.sh
tail = true
click-left = $HOME/.config/scripts/polybar-bluetooth.sh --toggle &
```
