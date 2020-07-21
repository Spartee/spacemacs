

## My Spacemacs Config

Below is a list of instructions for configuring my spacemacs on osx

My spacemacs config is under `spacemacs-config`

### Steps

 - brew tap d12frosted/emacs-plus
 - brew install emacs-plus@28 --with-spacemacs-icon
 - ln -s /usr/local/opt/emacs-plus@28/Emacs.app /Applications
 - mv ~/.emacs.d ~/.emacs.d.bak
 - git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
 - cd .emacs.d && git fetch origin release-0.200
 - git checkout release-0.200
 - mv spacemacs-config ~/.spacemacs
 - brew tap homebrew/cask-fonts && brew cask install font-source-code-pro


### Additional Packages
 - platinum searcher - brew install pt
 - ripgrep - brew install ripgrep
