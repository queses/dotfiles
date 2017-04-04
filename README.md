# Ratt's dot files.

### Vim:
`curl https://raw.githubusercontent.com/queses/dotfiles/master/.vimrc > ~/.vimrc`

### Tmux
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
curl https://raw.githubusercontent.com/queses/dotfiles/master/.tmux.conf > ~/.tmux.conf
tmux source ~/.tmux.conf
```
...or
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/queses/dotfiles/master/tmux.sh)"
```
After that, in tmux press prefix, Ctrl + I