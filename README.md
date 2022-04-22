
# Setup

## apt
```
$ sudo apt upgrade
$ sudo apt update
```

## Homebrew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ cd /path/to/win-provisioning
$ brew bundle
```

## dotfiles
```
$ ghq get  ueki-kazuki/dotfiles
$ cd /path/to/dotfiles
$ ./bootstrap.sh
```

## Cargo packages
```
$ sudo apt install zlib1g-dev
$ cargo install exa
$ cargo install bat
$ cargo install ripgrep
```

## neovim
```
$ apt install python3-pip -y
$ /usr/bin/python3 -m pip install pynvim
$ nvim  .config/nvim/init.vim

エラーがでるようなら :checkhealth で原因を調べる
```