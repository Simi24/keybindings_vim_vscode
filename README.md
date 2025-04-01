# VSCode Vim Configuration

My personal VSCode setup optimized for Vim users, featuring custom keybindings and settings for a more productive workflow.

## Installation

1. Clone this repository.
2. Copy files to the VSCode config directory:

   ```bash
   cp settings.json ~/.config/Code/User/
   cp keybindings.json ~/.config/Code/User/
   ```

## Vim Features

- **Leader key**: `<Space>`
- **System clipboard integration**
- **Relative line numbers**
- **Custom normal mode mappings**:
  - `<leader>w` - Save file
  - `<leader>q` - Quit
  - `<leader>x` - Save and quit
  - `<leader>v` - Vertical split
  - `<leader>s` - Horizontal split
  - `<leader>f` - Quick file search
  - `<leader>p` - Format document
  - `gh` - Show definition preview

## Navigation

### Terminal
- `Ctrl+Shift+T` - New terminal
- `Ctrl+Shift+W` - Close terminal
- `Ctrl+Shift+J` - Toggle terminal panel
- `Ctrl+Shift+A/B` - Next/Previous terminal

### File Explorer
- `Ctrl+E` - Toggle/Focus explorer
- `N` - New file
- `R` - Rename file
- `D` - Delete file

### Split Management
- `<leader>h/j/k/l` - Navigate splits
- `<S-h>/<S-l>` - Previous/Next buffer

## Visual Mode Features

- Stay in visual mode while indenting (`<`, `>`)
- Move selected lines (`J`, `K`)
- Toggle comments (`<leader>c`)
- Quick escape (`jk`)
