Window Manager
===

- Tweaking again around macos window manager!

yabai
---
https://github.com/koekeishiya/yabai/wiki
- `yabai --start-service`
- config file: `~/.config/yabai/yabairc`

skhdrc
---
https://github.com/koekeishiya/skhd/
- `skhd -V #debugging mode!
- config file: `~/.config/skhd/skhdrc`

- Examples:
 https://github.com/koekeishiya/skhd/blob/master/examples/skhdrc
```
# open terminal, blazingly fast compared to iTerm/Hyper
cmd - return : /Applications/kitty.app/Contents/MacOS/kitty --single-instance -d ~

# open qutebrowser
cmd + shift - return : ~/Scripts/qtb.sh

# open mpv
cmd - m : open -na /Applications/mpv.app $(pbpaste)
```

- Modifiers:
https://github.com/koekeishiya/skhd/issues/1
```
fn
cmd
lcmd
rcmd
shift
lshift
rshift
alt
lalt
ralt
ctrl
lctrl
rctrl
hyper (cmd + shift + alt + ctrl)
meh (shift + alt + ctrl)
```
