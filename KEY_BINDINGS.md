# Neovim Keybindings

This document outlines the custom keybindings configured in your Neovim setup.

## General Keybindings (`lua/anurag/core/keymaps.lua`)

| Mode | Keybinding | Description |
|------|------------|-------------|
| Insert | `jk` | Exit insert mode |
| Normal | `<leader>nh` | Clear search highlights |
| Normal | `<leader>+` | Increment number |
| Normal | `<leader>-` | Decrement number |
| Normal | `<leader>sv` | Split window vertically |
| Normal | `<leader>sh` | Split window horizontally |
| Normal | `<leader>se` | Make splits equal size |
| Normal | `<leader>sx` | Close current split |
| Normal | `<leader>to` | Open new tab |
| Normal | `<leader>tx` | Close current tab |
| Normal | `<leader>tn` | Go to next tab |
| Normal | `<leader>tf` | Open current buffer in new tab |

## Debugger (DAP) Keybindings (`lua/anurag/plugins/dap.lua`)

| Mode | Keybinding | Description |
|------|------------|-------------|
| Normal | `<leader>dt` | Toggle Breakpoint |
| Normal | `<leader>dc` | Continue |
| Normal | `<leader>dn` | Step Over |
| Normal | `<leader>di` | Step Into |
| Normal | `<leader>do` | Step Out |
| Normal | `<leader>dr` | Toggle REPL |
| Normal | `<leader>dl` | Run Last |
| Normal | `<leader>du` | Toggle DAP UI |
