# polybar-bluetooth

Based on [polybar/polybar-scripts/system-bluetooth-bluetoothctl](https://github.com/polybar/polybar-scripts/blob/master/polybar-scripts/system-bluetooth-bluetoothctl)

## output

- Power off

![poweroff](https://user-images.githubusercontent.com/25272630/184204004-7d229ab1-a450-42b4-bec4-9c85afd3cc30.png)
- Power on

![poweron](https://user-images.githubusercontent.com/25272630/184204051-12f93db8-4ee7-4956-9f3d-dc53dcd233e4.png)
- Connected

![connected](https://user-images.githubusercontent.com/25272630/184206818-2625c88f-8d1a-4fd5-b560-0c3238318d82.png)

## dependencies

- bluetoothctl
- nerdfonts

## module
```EditorConfig
[module/bt]
type = custom/script
exec = ~/scripts/polybar-bluetooth.sh
tail = true
click-left = ~/scripts/polybar-bluetooth.sh --toggle &
```
