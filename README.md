# spacevim-config
My personal spacevim configuration

## Clone this repo
- `cd ~/sources` (or any other location you prefer)
- `git clone https://github.com/buwaro/spacevim-config`

## Install neovim
### Mac
- `brew install neovim`

## Install spacevim
### Linux and Mac
- `git clone https://github.com/liuchengxu/space-vim.git ~/.space-vim`
- `cd ~/.space-vim`
- `make neovim`

## Install skim
### Mac
- `brew install sk`

## Install ripgrep
### Mac
- `brew install ripgrep`

## Use the spacevim config file
- **Remove the generated spacevim config:** `rm ~/.spacevim`
- **Symlink the spacevim config from the project:** `ln -s ~/sources/spacevim-config/.spacevim`

## Install plugins
- **Open nvim:** `nvim`
- **Install vim plugins:** `:PlugInstall`

## Use the tmux config file (optional)
- **Symlink the tmux config from the project:** `ln -s ~/sources/spacevim-config/.space-vim`
- **Reload the tmux config:** `tmux source-file ~/.tmux.conf`

## Setup Nerd fonts
### Mac
- download Hack nerdfont: https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
- extract the zip
- open the `font book` app
- file > add fonts > [select `Hack Bold Italic Nerd Font Complete.ttf`, `Hack Italic Nerd Font Complete.ttf`, `Hack Bold Nerd Font Complete.ttf` and `Hack Regular Nerd Font Complete.ttf`] > open
### linux
- download Hack nerdfont: https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
- extract the zip
- copy font files to `~/.local/share/fonts/`
- open alacritty and run `fc-cache -f -v`
- in alacritty, run `fc-list | grep "Hack"` to see if the font is installed


## Alacritty
> **note:** This config uses the Hack Nerd Font
- **Symlink alacritty config:** `ln -s ~/sources/spacevim-config/.alacritty.yml ~/.config/alacritty/.`
