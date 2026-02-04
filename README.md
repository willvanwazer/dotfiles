# Dotfiles

Personal configuration files.

## Installation

```bash
# Clone the repo
git clone git@github.com:willvanwazer/dotfiles.git ~/dotfiles

# Symlink tmux config
ln -sf ~/dotfiles/tmux.conf ~/.tmux.conf
```

## Configs

- **tmux.conf** - Tmux configuration with powerline-style status bar

## Tmux Keybindings

| Key | Action |
|-----|--------|
| `` ` `` | Prefix key |
| `` ` ` `` | Type literal backtick |
| `prefix + \` | Vertical split |
| `prefix + -` | Horizontal split |
| `prefix + h/j/k/l` | Navigate panes |
| `prefix + H/J/K/L` | Resize panes |
| `prefix + r` | Reload config |
