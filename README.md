off yay requirement:
legit wallpaper engine
p.s. starship must be added to .bashrc
Bash

Add the following to the end of ~/.bashrc:
```
# ~/.bashrc

eval "$(starship init bash)"
```
Fish

Add the following to the end of ~/.config/fish/config.fish:
```
# ~/.config/fish/config.fish

starship init fish | source
```
Zsh

Add the following to the end of ~/.zshrc:
```
# ~/.zshrc

eval "$(starship init zsh)"
```
