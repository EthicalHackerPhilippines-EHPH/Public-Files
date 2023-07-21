# Requirements
## Installation 
```sh
# resources
# goclone
https://github.com/imthaghost/goclone
https://www.goclone.io/

# brew installation and config
https://linuxconfig.org/how-to-install-brew-on-linux

STEP 1:
$ sudo apt update
$ sudo apt install build-essential curl git

STEP 2:
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

STEP 3:
$ echo 'eval "$(/home/kali/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
$ eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"

STEP 4:
$ brew doctor 
Your system is ready to brew

STEP 5: 
Install goclone 
$ brew tap imthaghost/goclone 
$ brew install goclone 

STEP 6:
Testing goclone 
$ goclone --help, -h

STEP 7:
# clone test
# Use current directory
$ goclone www.facebook.com/login.php
$ cd www.facebook.com
```
