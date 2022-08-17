# Jenin's dotfiles

## Contents

- Neovim
- Powershell

## Neovim

#### Install version 0.7.2 on linux

You can Install Neovim using the standard apt package manager but it will only install neovim version 0.4.3 which uses `VimScript` as the configuration language and cannot be configured using the `Lua` programming language.

To install the latest version. Use apt-get

`sudo add-apt-repository ppa:neovim-ppa/stable sudo apt-get update sudo apt-get install neovim`

#### Plugins

Requires Neovim (>= 7.0)

- ['wbthomason/packer.nvim'](https://github.com/wbthomason/packer.nvim) - A plugin manager for Neovim
- ['svrana/neosolarized.nvim'](https://github.com/svrana/neosolarized.nvim) - Neosolarized theme for Neovim
- ['nvim-lualine/lualine.nvim'](https://github.com/nvim-lualine/lualine.nvim) - A status line written in lua
- ['onsails/lspkind-nvim'](https://github.com/onsails/lspkind.nvim) - Gives VSCode like pictograms
- ['hrsh7th/cmp-buffer'](https://github.com/hrsh7th/cmp-buffer) - Nvim-Cmp source for buffer words
- ['hrsh7th/cmp-nvim-lsp'](https://github.com/hrsh7th/cmp-nvim-lsp) - Nvim-Cmp source for neovim's builtin LSP
- ['hrsh7th/nvim-cmp'](https://github.com/hrsh7th/nvim-cmp) - A completion engine plugin for neovim written in Lua
- ['neovim/nvim-lspconfig'](https://github.com/neovim/nvim-lspconfig) - A collection of configurations for Neovim's built-in LSP
- ['evanleck/vim-svelte'](https://github.com/evanleck/vim-svelte) - Syntax highlighting for Svelte files
- ['nvim-treesitter/nvim-treesitter'](https://github.com/nvim-treesitter/nvim-treesitter) - Treesitter configuration and abstraction layer for nvim
- ['nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - A highly extendable fzf over lists
- ['nvim-telescope/telescope-file-browser.nvim](https://github.com/nvim-telescope/telescope-file-browser.nvim) - File browser extension for telescope.nvim
- ['nvim-lua/plenary.nvim'](https://github.com/nvim-lua/plenary.nvim) - Common utilities
- ['L3MON4D3/LuaSnip'](https://github.com/L3MON4D3/LuaSnip) - Snippet Engine for Neovim written in Lua
- ['windwp/nvim-autopairs'](https://github.com/windwp/nvim-autopairs) - AutoParis
- ['windwp/nvim-ts-autotag'](https://github.com/windwp/nvim-ts-autotag) - AutoTag using Treesitter support
- ['kyazdani42/nvim-web-devicons'](https://github.com/kyazdani42/nvim-web-devicons) - Custom Icons for fzf and tabs
- ['akinsho/nvim-bufferline.lua'](https://github.com/akinsho/bufferline.nvim) - A snazzy bufferline
