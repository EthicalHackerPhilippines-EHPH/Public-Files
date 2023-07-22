# Requirements for Installation 
```sh
https://github.com/imthaghost/goclone
https://www.goclone.io/

$ sudo apt update
$ sudo apt install build-essential curl git

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

$ echo 'eval "$(/home/kali/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
$ eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"

$ brew doctor 
Your system is ready to brew

# Installing goclone 
$ brew tap imthaghost/goclone 
$ brew install goclone 

# goclone help command 
$ goclone --help, -h

# clone test
# Use current directory
$ goclone https://www.example.com/login.php
```
