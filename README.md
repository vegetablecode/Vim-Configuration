# VIM

This is my Vim configuration for general web development.  

# Installation

## NeoVim

1. GOTO: [https://neovim.io/](https://neovim.io/)
2. Install NeoVim

## Configuration

1. GOTO: ~/.config/nvim
2. Copy-Paste init.vim
3. Copy-Paste coc-settings.json

## Coc plugins

Additionally you'll need to install some Coc extensions...

1. "Esc" to enter normal mode
2. Type the command below

```jsx
:CocInstall coc-eslint coc-prettier coc-tailwindcss coc-html coc-json coc-css coc-tsserver
```

All my coc plugins:
- coc-marketplace
- coc-eslint
- coc-highlight
- coc-emmet
- coc-prettier
- coc-snippets
- coc-tailwindcss
- coc-html
- coc-json
- coc-tslint-plugin
- coc-css
- coc-server

# Some Nice Commands

## MISC

- `,` - Map leader, nearly all my custom mappings starts with pressing the comma key
- `,q` - Sidebar filetree viewer (NERDTree)
- `,ee` - Change colorscheme (with fzf fuzzy finder)
- `,s` - New terminal in horizontal split
- `,vs` - New terminal in vertical split
- `,f` - Fuzzy find a file (fzf)
- `<Tab>` - Next buffer
- `<Shift-Tab>` - Previous buffer
- `<Ctrl-w>` - Switch between terminals

## Coc

- `[g` - Prev diagnostic
- `]g` - Next diagnostic
- `,p` - Format with Prettier
- `,do` - Show code actions
- `<Space-d>` - show all warnings etc.