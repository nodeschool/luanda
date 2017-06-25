# Tutorial para instalar o NodeJS

##Instalar Node no Mac
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