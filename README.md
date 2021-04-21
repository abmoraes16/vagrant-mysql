# Projeto vagrant-mysql
Esse repositório tem como objetivo subir uma máquina virtual utilizando Vagrant com MySql instalado, devendo ser acessível pelo host na porta 3306.

## Requisitos
* VirtualBox
* Vagrant

## Execução
Após efetuado o clone do projeto, para iniciar a VM, é necessário rodar o comando:
* vagrant up

## Testar o MySql
Por SSH:
* vagrant ssh
* sudo mysql -uroot

Por interface gráfica:
* Apontar para endereço localhost:3306, usuário root

