# Exercícios MongoDB
Repositório com exercícios resolvidos e um cheat sheet pessoal de MongoDB

## Comandos

#### Instalando
Para mais detalhes acesse o [site oficial](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/#install-mongodb-community-edition)
```sh
$ sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927

$ echo "deb http://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.2.list

$ sudo apt-get update

$ sudo apt-get install -y mongodb-org
```

#### Executando
```sh
$ sudo service mongod start
```
