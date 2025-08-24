# my-fedora-setup

## Theme
Nordic Darker

## Fonts
```
sudo dnf install cascadia-mono-nf-fonts
```

## Programs
```
sudo dnf install afetch bat lsd rlwrap tcllib
```
#### Fancy-git
[https://github.com/diogocavilha/fancy-git]

## .bashrc
```
alias cat="bat"
alias ls="lsd"
alias l="lsd -l"
alias la="lsd -a"
alias lla="lsd -la"
alias lt="lsd --tree"
alias gsim="rlwrap tclsh"
afetch
```
