# tmuxconf

## Place it

```
git clone https://github.com/ngicks/tmuxconf ~/.config/tmux
```

## Notable configurations

- `set -g default-terminal 'xterm-256color'`:
  - The old tmux set $TERM `screen`. as of Ubuntu 24.04, the current version of
    tmux place it to tmux-256color.
  - Some old software deems it as a lack of capability and launch in broken
    state.
  - `xterm-256color` is causing no trouble at this moment.
- vim like copy mode.
- nvim like pane move: prefix+{h,j,k,l} to move around
- nvim like pane split: prefix+s to split horizontally, prefix+v to virtically
