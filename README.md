# polybar-bluetooth
Based on "polybar-scripts/polybar-scripts/system-bluetooth-bluetoothctl", it broke after a update and this is my attempt fixing it

[module/bt]
type = custom/script
exec = $HOME/.config/scripts/polybar-bluetooth.sh
tail = true
click-left = $HOME/.config/scripts/polybar-bluetooth.sh --toggle &
