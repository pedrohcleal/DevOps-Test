# Projeto devops Frexco

Projeto introdutório para subir uma aplicação(deploy) API em Django + PostgreSQL com a utilização de containers da ferramenta Docker

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **Implantação** para saber como implantar o projeto.

### 📋 Pré-requisitos

```
Docker -> https://docs.docker.com/get-docker/
Python -> https://www.python.org/downloads/
Django -> executar comando ```shell pip install django ```
PostGreeSQL -> https://www.postgresql.org/download/
Dbeaver -> https://dbeaver.io/download/
Git -> https://git-scm.com/downloads
```

### 🔧 Instalação

Para iniciar a aplicação, é necessário clonar o projeto do GitHub num diretório de sua preferência:

```shell
cd "diretorio de sua preferencia"
git clone https://github.com/pedrohcleal/github.git
```

Após clonar, execute os seguintes passos:

```
Abrir o PowerShell no diretório primário e executar o seguinte comando para a aplicação django executar:
docker-compose up

Abrir outro terminal e executar a linha de comando para a aplicação nginx abrir:
docker container run --name ws1 -p 8000:80 -d nginx

```

## ⚙️ Executando os testes

Para verificar se o Django subiu corretamente acesse pelo navegador o seguinte endereço: http://localhost:5000/

Para verificar se o Nginx subiu corretamente acesse pelo navegador o seguinte endereço: http://localhost:8080/

Para verificar se o banco de dados foi criado corretamente:
1- Abrir dbeaver
2- Clique em New Database Connection, escolha PostGreSQL
3- insira as seguintes informações de server -> Host: localhost port: 5432
4- insira as credenciais -> username: postgres password: postgres
5- O banco de dados será aberto em seguida.

## 📦 Desenvolvimento

A aplicação tem como objetivo subir um container como uma aplicação em django com banco de dados, tornando-se de ótima escolha para um software 
devido a sua escalabilidade e possibilidade de uso de diferentes imagens tornado-se compatível com praticamente qualquer tipo de SO, assemelhando-se a uma VM
com o uso do Docker e para a manipulação e uso de dados com PostgreSQL + Python.

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* PowerShell
* PostgreSQL
* Virtual Studio Code
* Github

## 🖇️ Colaborando

Por favor, leia o [COLABORACAO.md](https://gist.github.com/usuario/linkParaInfoSobreContribuicoes) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

## 📌 Versão

Primeira Versão

## ✒️ Autor

Pedro Leal

## 🎁 Expressões de gratidão

* A minha experiência com esse projeto foi de abrir menter, puder conhecer na prática uma das principais ferramentas utilizadas por DevOps como o Docker
* aprofundei ainda mais meu conhecimento sobre Python e sua biblioteca Django para implementação WEB
* Obtive um maior entendimento sobre o uso do Github para versionamento e sincronização
* Soube de boas práticas com o uso do Continuous Integration e Continuos Delivery, afim de aplicar as metodologias ágeis no versionamento de código.

---
Atenciosamente, Pedro Leal
