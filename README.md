# Dotfiles

Personal configuration files.

## Installation

```bash
# Clone the repo
git clone git@github.com:willvanwazer/dotfiles.git ~/dotfiles

# Symlink configs
ln -sf ~/dotfiles/tmux.conf ~/.tmux.conf
ln -sf ~/dotfiles/nvim ~/.config/nvim
```

## Configs

- **tmux.conf** - Tmux with powerline status bar and Claude integration
- **nvim/** - Neovim with lazy.nvim, Catppuccin theme, and essential plugins

## Tmux Keybindings

| Key | Action |
|-----|--------|
| `` ` `` | Prefix key |
| `` ` ` `` | Type literal backtick |
| `prefix + \` | Vertical split |
| `prefix + -` | Horizontal split |
| `prefix + h/j/k/l` | Navigate panes |
| `prefix + H/J/K/L` | Resize panes |
| `prefix + c` | New window with Claude |
| `prefix + C` | Claude in vertical split |
| `prefix + v` | Enter copy mode |
| `prefix + r` | Reload config |

## Neovim Keybindings

Leader key: `Space`

| Key | Action |
|-----|--------|
| `<leader>e` | Toggle file explorer |
| `<leader>ff` | Find files |
| `<leader>fg` | Live grep |
| `<leader>fb` | List buffers |
| `<leader>fr` | Recent files |
| `<leader>cc` | Toggle Claude terminal |
| `<leader>w` | Save file |
| `<leader>q` | Close buffer |
| `<leader>sv` | Vertical split |
| `<leader>sh` | Horizontal split |
| `Ctrl+\` | Toggle terminal |
| `Shift+h/l` | Previous/next buffer |
| `gc` | Toggle comment |

## Neovim Plugins

- **catppuccin** - Color scheme
- **nvim-tree** - File explorer
- **telescope** - Fuzzy finder
- **treesitter** - Syntax highlighting
- **gitsigns** - Git integration
- **lualine** - Status line
- **bufferline** - Buffer tabs
- **toggleterm** - Terminal (with Claude integration)
- **which-key** - Keybinding hints
- **Comment.nvim** - Comment toggling
- **nvim-autopairs** - Auto close brackets
- **indent-blankline** - Indent guides
