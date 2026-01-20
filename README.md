# vscode-nvim-numbertoggle

Neovim plugin to automatically toggle between relative and absolute line numbers in VSCode. Written in Lua.

![demo](https://user-images.githubusercontent.com/56180050/177167997-652a43b1-c94a-4b73-94d6-e4b85fbd4606.gif)

Relative numbers are used in a buffer that has focus and is in normal mode since that's where you move around. They're turned off when you switch out of Vim, switch to another split, or go into insert and command modes.

## Getting started

### Requirements

- Neovim 0.7 or later
- [VSCode Neovim](https://github.com/vscode-neovim/vscode-neovim)

### Installation

Use your favorite package manager. Example config with built-in vim.pack:

```lua
vim.pack.add({
	{ src = "https://github.com/vscode-neovim/vscode-neovim" },
	{ src = "https://github.com/mous16/vscode-nvim-numbertoggle" }
})
```

## Acknowledgment

Based on [nvim-numbertoggle](https://github.com/sitiom/nvim-numbertoggle)
