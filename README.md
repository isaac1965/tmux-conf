![Captura desde 2023-09-29 18-11-54](https://github.com/isaac1965/tmux-conf/assets/44930181/2d6aba7e-01ca-4b5e-83f4-ccb54a782654)

                                               
```sh
unbind %
bind | split-window -h 

unbind '"'
bind - split-window -v

unbind r
bind r source-file ~/.tmux.conf

bind j resize-pane -D 5
bind k resize-pane -U 5
bind l resize-pane -R 5
bind h resize-pane -L 5

bind -r m resize-pane -Z
```
