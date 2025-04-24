# ubuntu-kernel-update
Realizar atualização do Kernel Linux na distribuição Ubuntu Server ou Desktop.
O procedimento foi realizado na versão Ubuntu 20.04 LTS Minimal. Trata-se da ultima ISO disponibilizada com tamanho mínimo sendo 80MB.

Para atualizar versão Ubuntu para 22.04 LTS utilize.

sudo do-release-upgrade

1- Adicione o repositório.

sudo add-apt-repository ppa:cappelikan/ppa

2- Instale mainline

sudo apt install mainline

3- Verifique qual ultimo Kernel disponível.

sudo mainline check 

4- Instale a ultima versão disponível.

sudo mainline install-latest

Após concluir procedimento verifique a versão Kernel linux através do comando.

uname -r 
