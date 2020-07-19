# dotfiles
dotfiles skeletons to make my life on *NIX saner :)

Usage
-----
Usage is simple
  ```console
    $ git clone --depth 1 -j $(nproc) --no-tags https://github.com/sreekanthj93/dotfiles.git "$HOME/.dotfiles"
    $ $HOME/.dotfiles/script/bootstrap
  ```

Finally to get aliases add below lines in .bashrc or .zshrc
1. For Bash
  ```console
    source ~/.bashrc_my
  ```
2. For Zsh
  ```console
    source ~/.zshrc_my
  ```
