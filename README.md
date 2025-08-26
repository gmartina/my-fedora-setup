# my-fedora-setup

## Theme
Nordic Darker

## Fonts
```
sudo dnf install cascadia-mono-nf-fonts
```

## Programs
```
dnf install afetch bat lsd rlwrap tcllib
dnf install meson gperf flex glib2-devel gcc gcc-c++ gtk3-devel \
            gobject-introspection-devel desktop-file-utils tcl gtkwave
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
