# polybar playerctl module
a polybar module that displays current playing song and play/pause controls using playerctl

### usage
place the `playerctl.sh` file wherever your heart pleases, then in your polybar config, write these lines (as well as add the module in your modules list):

```
[module/playerctl]
type = custom/script
exec = $HOME/your_playerctl_sh_location.sh
interval = 0.5
label-foreground = #ffffff
```
