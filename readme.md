# documentação da API

* Escolher um local do computador para criar o projeto
* abrir o gitbash nesta pasta

Com o gitbash aberto executar o comando para criar a raiz do projeto:
```
mkdir NOME_PROJETO
```
Acessar a pasta
```
cd NOME_PROJETO
```
Comando para abrir o VSCode
```
code .
```
Criar o arquivo gerenciador de pacotes node
```
npm init -y
```
touch .gitignore
```
Criar arquivo .env: arquivo para reservar variáveis do projeto
```
touch .env

#Instalar os pacotes do projeto
```
npm i express nodemon dotenv
```
* express: será o servidor de API
* nodemon: atualizar os arquivos alterados sem parar o servidor
* dotenv: gerenciador de variáveis de ambiente

Criar pasta
```
mkdir src
```
Criar arquivo server.js
```
adicionair arquivos e pastas no gitignore
```
node_modules
.env
```
Adicionar a porta do servidor no arquivo env.
```
PORT = 3004
```