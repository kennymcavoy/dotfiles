# My Dotfiles

Clone to a directory (ex. Dotfiles) and use stow to move easily
(Brew install)

## Installing

You will need `git` and GNU `stow`

Clone into your `$HOME` directory or `~`

```bash
git clone repo ~
```

Run `stow` to symlink everything or just select what you want

```bash
stow */ # Everything (the '/' ignores the README)
```

```bash
stow zsh # Just zsh config
```
