# macOS
Tips, Scripts related to macOS


## Chrome
https://www.google.com/chrome/

## iTerm2
https://www.iterm2.com/downloads.html

## Sublime
https://www.sublimetext.com/

## Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```
$ brew list| sort | tr '\n' ' '
azure-cli convertlit freetype gdbm ghostscript go htop imagemagick jpeg libao libevent libpng libtiff libtommath \
libtool little-cms2 mas openssl p7zip pkg-config python python3 qpdf readline sphinx-doc sqlite tmux uade wget xz
```

## Install software via App Store using a command-line based tool
* mas is'nt working for deploying free software (needs to be debgugged)
```
$ mas install 470158793 777221999 803453959 1278508951
# 470158793 Keka (1.0.15) Paid
# 777221999 NewFileHere (2.4) Paid
# 803453959 Slack (3.1.1) Free
# 1278508951 Trello (2.10.3) Free
```

## WineBottler
http://winebottler.kronenberg.org/downloads

## gcloud & gsutil
```
curl https://sdk.cloud.google.com | bash
```

## aws-cli
* https://github.com/aws/aws-cli
```
pip install awscli
pip install --upgrade awscli
aws configure
```

## Discord
https://discordapp.com/api/download?platform=osx
