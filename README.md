# Dotfiles

## installation

1. clone this repo to your HOME directory
2. add to your `~/.profile` or similar this line:

```bash
test -s "$HOME/dotfiles/.main" && source "$HOME/dotfiles/.main"
```

## update

```bash
$ cd ~/dotfiles
$ git pull
```

```
$ source .profile
```

## TODO

- [ ] use this [template](https://github.com/anishathalye/dotfiles_template) 

## pending aliases

- [ ] reload dotfiles helper
- [ ] copy sam dotfiles

## Installer

- [ ] tldr
- [ ] shellcheck
- [ ] fzf
- [ ] tree
- [ ] broot
- [ ] vim
- [ ] [bashtop](https://github.com/aristocratos/bashtop#installation)
