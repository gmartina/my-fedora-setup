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
alias ls="lsd --blocks permission,user,group,size,name"
alias l="lsd -la --blocks permission,user,group,size,name"
alias la="lsd -a --blocks permission,user,group,size,name"
alias lla="lsd -la --blocks permission,user,group,size,name"
alias lt="lsd --tree --depth 4"
alias gsim="rlwrap tclsh"
alias github="cd ~/github"
alias repo=github
alias home="cd ~"
alias ..="cd .."
alias ...="cd ../.."
alias ....="cd ../../.."
alias update='sudo dnf upgrade --refresh -y'
alias install='sudo dnf install -y'
alias venv='python -m venv .venv && echo "✅ .venv created. Run: source .venv/bin/activate"'
alias vact='source .venv/bin/activate && echo "✅ Virtual environment activated: .venv"'

alias vdeact='deactivate && echo "🚫 venv deactivated"'
alias vbash='vim ~/.bashrc'
alias reload='source ~/.bashrc && echo "✅ Bash configuration reloaded!"'

afetch

```
