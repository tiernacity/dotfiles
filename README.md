# Install
1. `git clone --bare <this-repo> $HOME/.cfg`
1. `alias config='git -c status.showUntrackedFiles=no --git-dir=$HOME/.cfg/ --work-tree=$HOME'`
1. `config checkout # fix "files would be overwritten by checkout" errors`
1. Add `. ~/.chris` to `.bashrc` or `.zshrc`, login again (or source the `.rc` file)
1. Use the `config` shell alias to manage dotfiles
1. Use `bin/install` to install common packages
1. Install neovim, others as required

# Reference
- https://www.atlassian.com/git/tutorials/dotfiles
