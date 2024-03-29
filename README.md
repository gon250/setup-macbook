# setup-macbook

Personal macbook setup.
## Brew 
- xcode-select --install (this step not required, as brew installs it for you)
- Install Brew
    - [https://brew.sh/](https://brew.sh/)
    - iterm2
    - fzf
    - git
    - rectangle
    - alfred
    - google-chrome
    - firefox
    - docker
    - brew install --cask iina
    - postman
    - notion
    - [tree](https://formulae.brew.sh/formula/tree)
    - [alt-tab-macos](https://github.com/lwouis/alt-tab-macos)
## Shell
re-install zsh by brew
- ``$ brew install zsh``

Update default shell to be Homebrew’s Zsh
- ``$ sudo vim /etc/shells``
- Add ``/usr/local/bin/zsh``
- Run ``$ chsh -s /usr/local/bin/zsh``
  - Extra:
  - [https://ohmyz.sh/](https://ohmyz.sh/)
  - [https://github.com/romkatv/powerlevel10k](https://github.com/romkatv/powerlevel10k)


Extra config for ``.zshrc``
- plugins=(git brew docker docker-compose dotenv npm osx)
- https://github.com/zsh-users/zsh-syntax-highlighting
  - source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh

- https://github.com/zsh-users/zsh-autosuggestions
  - source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh

## Node 
Install node by ``nvm``
Updated: brew is not working at all, so use https://github.com/lukechilds/zsh-nvm

# SSH 
Configure ssh 

``$ mkdir ~/.ssh && touch ~/.ssh/config``

# Extra Apps
- [https://github.com/exelban/stats][https://github.com/exelban/stats]
- [https://matthewpalmer.net/vanilla/](https://matthewpalmer.net/vanilla/)
