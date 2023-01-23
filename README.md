# nordic.nvim

A Neovim colorscheme based on [Nord](https://www.nordtheme.com/), but `Aurora` > `Frost`.  

The idea behind this colorscheme is to use Nord, but add some darker colors and use `Aurora` more prominently than Nord themes usually do.

# ⚠️ Status

This colorscheme is still early in development, so please do not hesitate if there is anything wrong or if you have any suggestions!  Currently I am [dogfooding](https://en.wikipedia.org/wiki/Eating_your_own_dog_food) it to make sure I did not miss anything.

# 📷 Showcase

*Nvim-tree, bar-bar, lualine and treesitter:*
![image](https://user-images.githubusercontent.com/81622310/213918910-7e9e4068-3eef-4d68-b192-4b0200cc1631.png)

<details>
<summary>Telescope</summary>

*Flat:*
![image](https://user-images.githubusercontent.com/81622310/213918343-a4daac04-9e98-4ba1-89f8-0e8eb4b73c10.png)
*Classic:*
![image](https://user-images.githubusercontent.com/81622310/213974295-c9381a16-6f02-49dd-88b3-64f03ef9d5c7.png)

</details>

# 🎨 Palette

TODO

# 📦 Installation

With [packer.nvim](https://github.com/wbthomason/packer.nvim):

```lua
use 'AlexvZyl/nordic.nvim'
```

With [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'AlexvZyl/nordic.nvim', { 'branch': 'main' }
```

# 🚀 Usage

Using a Neovim command:

```vim
colorscheme nordic
```

Using lua:

```lua
require 'nordic' .load()
-- or
vim.cmd [[colorscheme nordic]]
```

Using `Nordic` with `Lualine`:

```lua
require 'lualine' .setup {
  options = {
    theme = 'nordic'
  }
}
```

# ⚙️ Configuration

Below is the default configuration.

> 

```lua
require 'nordic' .setup {
  telescope = {
    -- Available styles: `classic`, `flat`.
    style = 'flat'
  }
}
```

# 🗒️ Supported Plugins

This is the list of currently supported plugins.  I use these myself, if you want other plugins to be supported either open an issue or submit a PR!

- [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)
- [barbar.nvim](https://github.com/romgrk/barbar.nvim)
- [nvim-dap](https://github.com/mfussenegger/nvim-dap)
- [nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui)
- [dashboard-nvim](https://github.com/glepnir/dashboard-nvim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [leap.nvim](https://github.com/ggandor/leap.nvim)
- [lspsaga.nvim](https://github.com/glepnir/lspsaga.nvim)
- [nvim-tree.lua](https://github.com/nvim-tree/nvim-tree.lua)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [trouble.nvim](https://github.com/folke/trouble.nvim)
- [which-key.nvim](https://github.com/folke/which-key.nvim)

# 🎙️ Acknowledgements

- [folke/tokyonight](https://github.com/folke/tokyonight.nvim) served as an excellent example for a Neovim theme.
- [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) for bright & dim versions of the Nord palette.

