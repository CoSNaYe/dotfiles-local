# dotfile_local
Additional Terminal and Vim settings for [Thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles)

## Install
1. Install [Thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles)
2. Clone this project into ~/dotfiles-local
3. To enable YouCompleteMe, follow [YouCompleteMe](https://github.com/Valloric/YouCompleteMe#installation) to install
    * If install Python by Anaconda, then we should follow the instruction [here](https://github.com/Valloric/YouCompleteMe/issues/1241#issuecomment-335051278)
4. To enable AutoFormat, follow [AutoFormat](https://github.com/Chiel92/vim-autoformat#default-formatprograms) to enable supports for languages
    * Javascript/JSON, ESlint, sass-convert, rbeautify, remark
5. Install powerline font
    * `brew tap homebrew/cask-fonts`
    * `brew install --cask font-hack-nerd-font`
6. Install [base16-shell](https://github.com/chriskempson/base16-shell)
    * Then run `base16_tomorrow-night` once

7. Install [Ag](https://github.com/ggreer/the_silver_searcher)

## Options
### Markdown support in Vim
1. Follow the instructions to install [vim-instant-markdown](https://github.com/suan/vim-instant-markdown)

### Autojump (a faster way to navigate your filesystem)
1. Follow the instructions to install [Autojump](https://github.com/wting/autojump#name)
### Enable zsh plugins
1. Install [Zplug](https://github.com/zplug/zplug#user-content-using-homebrew-os-x)
    * Use the curl one not homebrew
2. Use `zplug install` to install your plugins and run `source ~/.zshrc`

