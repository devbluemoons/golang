## install
```console
# Max OS
brew install go

# ubuntu
sudo apt-get install golang-go
```

## check installed
```console
# version
go version

# which
which go
```

## set PATH
```sh
# bash > $HOME/.profile
# zsh > $HOME/.zshrc

export GOPATH=$HOME
export PATH=$PATH:$GOPATH/bin
```
