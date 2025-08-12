# Obligatorio
Obligatorio Taller Linux 2025

# Tareas a realizar:

## 1- Instalar git con el comando:

  sudo apt install git

## 2- Instalar ansible:

  sudo dnf install ansible-core

## 3- Instalamos ansible requirements:

   ansible-galaxy install -r collections/requirements.yaml

## 4- Generar clave SSH:

   ssh-keygen


## 5- Clonar el GIT por HTTPS

   git clone https://github.com/Plaga34/Obligatorio.git


## 6- Instalamos y habilitamos SSH Ubuntu Server:

  sudo dnf install openssh-server
  
  sudo systemctl start ssh

  sudo systemctl enable ssh


## 7- Copiar las Claves ssh

   ssh-copy-id 192.168.1.2
  
   ssh-copy-id 192.168.1.3


## 8- Ejecutamos el Playbook:

  ansible-playbook playbook/nfs_shared.yml -K


## 9-  Ejecutamos el Playbook:

  ansible-playbook playbook/hardening.yml -K

