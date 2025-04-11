# Infrastructure as Code

## Wordpress com Ansible

Criar 3 máquinas virtuais com a imagem iso do Ubuntu Server (com a configuração de rede: "Conectado a Placa em modo Bridge"):

### 1. Máquina virtual para executar o Ansible: 

* Instalar Ansible 

* Criar 2 chaves ssh para comunicar com as outras 2 máquinas virtuais

* Comando para executar o PlayBook do Ansible:

```
    ansible-playbook provisioning.yml -i hosts -K
```

### 2. Máquina virtual para executar o servidor do Wordpress

### 3. Máquina virtual para executar o banco de dados MySQL
