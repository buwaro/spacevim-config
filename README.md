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

## Use the spacevim config file
- **Remove the generated spacevim config:** `rm ~/.spacevim`
- **Symlink the spacevim config from the project:** `ln -s ~/sources/spacevim-coinfig/.space-vim`

## Install plugins
- **Open nvim:** `nvim`
- **Install vim plugins:** `:PlugInstall`

## Use the tmux config file (optional)
- **Symlink the tmux config from the project:** `ln -s ~/sources/spacevim-coinfig/.space-vim`
- **Reload the tmux config:** `tmux source-file ~/.tmux.conf`
