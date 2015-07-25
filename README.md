# Dotfiles

## Terminal install
- Install the included `DroidSansMono.ttf` font.
- Install [iTerm2](https://www.iterm2.com).
- Configure `DroidSansMono` as terminal font.
- `cp gitignore_global ~/.gitignore_global`
- `git config --global core.excludesfile ~/.gitignore_global`

## Vim install
- Install macvim: `brew install macvim`.
- Install [janus](https://github.com/carlhuda/janus).

```bash
# clone additional vim plugins
cd ~/.janus
git clone https://github.com/vim-scripts/Align.git
git clone https://github.com/othree/html5.vim.git
git clone https://github.com/myusuf3/numbers.vim.git
git clone https://github.com/rstacruz/sparkup.git
git clone https://github.com/godlygeek/tabular.git
git clone https://github.com/bling/vim-airline.git
git clone https://github.com/heartsentwined/vim-emblem
git clone https://github.com/jtratner/vim-flavored-markdown.git
git clone https://github.com/nono/vim-handlebars.git
git clone https://github.com/mxw/vim-jsx.git
git clone https://github.com/groenewege/vim-less.git
git clone https://github.com/slim-template/vim-slim.git
git clone https://github.com/szw/vim-tags.git
git clone https://github.com/nelstrom/vim-textobj-rubyblock.git
git clone https://github.com/kana/vim-textobj-user.git
git clone https://github.com/mattn/zencoding-vim.git
git clone https://github.com/Townk/vim-autoclose.git

# overwrite the default janus configuration
cp vimrc.before ~/.vimrc.before
cp vimrc.after ~/.vimrc.after
```

## OhMyZsh configuration
- Install [ohmyzsh](http://ohmyz.sh).

```bash
cp juanda.zsh-theme ~/.oh-my-zsh/themes/juanda.zsh-theme # zsh theme
cp zshrc ~/.zshrc                                        # zsh config file
```

