# Tutorial para instalar o NodeJS

## Instalar Node no Mac
Passo a passo:

Tenha a certeza de teres todos os build tools C++ instalados, para tal, instale o Xcode.

Abra o terminal e rode os seguintes comandos:
```
$ xcode-select --install
#uma janela irá abrir, escolha install
#aguarde a instalação se completar

$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash

$ source ~/.bash_profile

$ nvm on
$ nvm install stable

$ nvm list

$ nvm use <versao retornada no comando anterior>
```

## Instalar Node no Ubuntu
Passo a passo:
```
$ sudo apt-get update
$ sudo apt-get install build-essential libssl-dev

$ curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh

$ bash install_nvm.sh

$ source ~/.profile

$ nvm on
$ nvm install stable

$ nvm list

$ nvm use <versao retornada no comando anterior>
```

## Instalar Node no Windows
Passo a passo:

Baixe esse executável_ https://github.com/coreybutler/nvm-windows/releases/download/1.1.5/nvm-setup.zip

descompacte e instale no diretório C:\nodejs
abra o cmd do windows e rode os seguintes comandos:
--------Rodar no cmd--------
```
nvm arch 64  #para pc 64 bits
nvm arch 32  #para pc 32 bits
nvm on

nvm install stable

nvm list

nvm use <versao retornada no comando anterior>
```
