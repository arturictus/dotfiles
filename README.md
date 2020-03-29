# Dotfiles

## installation

1. clone this repo to your HOME directory
2. add to your `~/.profile` or similar this line:

```bash
test -s "$HOME/dotfiles/.main" && source "$HOME/dotfiles/..main"
```

## update

```bash
$ cd ~/dotfiles
$ git pull
```

```
$ source .profile
```