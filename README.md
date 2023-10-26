# Install
1. `git clone --bare <this-repo> $HOME/.dotfiles`
1. `alias dotfiles='git -c status.showUntrackedFiles=no --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'`
1. `dotfiles checkout # fix "files would be overwritten by checkout" errors`
1. Use `bin/install` to install base/common packages
1. Add `. ~/.chris` to `.bashrc` or `.zshrc`, login again (or source the `.rc` file)
1. Use the `dotfiles` shell alias to manage dotfiles

# Reference
- https://www.atlassian.com/git/tutorials/dotfiles
