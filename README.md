# Установка NeoVim
        brew install neovim

# Установка LunarVim
- [сайт](https://www.lunarvim.org/docs/installation)

        LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)
        mkdir -p ~/.local/share/fonts
        cd ~/.local/share/fonts && curl -fLO https://github.com/ryanoasis/nerd-fonts/raw/HEAD/patched-fonts/DroidSansMono/DroidSansMNerdFont-Regular.otf

# Настройка LunarVim
        ~/.config/lvim/config.lua
        vim.cmd [[autocmd VimEnter * NvimTreeOpen]]
        vim.cmd [[autocmd VimEnter * set mouse=a]]