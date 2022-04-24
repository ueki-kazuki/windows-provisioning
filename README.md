
# Setup

## Chocolatey
```
PS> choco install adobereader
PS> choco install joplin
PS> choco install powertoys
PS> choco install slack
PS> choco install sysinternals
PS> choco install vscode
```

## Update WSL
```
PS> wsl --update
PS> wsl --shutdown
```

## apt
```
$ sudo apt upgrade
$ sudo apt update
```

## Homebrew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ cd /path/to/windows-provisioning
$ brew bundle
```

## dotfiles
```
$ ghq get ueki-kazuki/dotfiles
$ cd /path/to/dotfiles
$ ./bootstrap.sh
```

## Cargo packages
```
$ sudo apt install zlib1g-dev
$ cargo install exa
$ cargo install bat
$ cargo install ripgrep
$ cargo install fd-find
```

## neovim
```
$ apt install python3-pip -y
$ /usr/bin/python3 -m pip install pynvim
$ nvim  .config/nvim/init.vim
```

エラーがでるようなら :checkhealth で原因を調べる
