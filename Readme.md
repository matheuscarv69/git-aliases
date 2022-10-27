# 👾 Git Aliases 🤖

Esse repositório trata-se de um tutorial de como criar e utilizar aliases no Git Bash. Além de fornecer um arquivo **.bashrc** como exemplo e pronto para uso.

## 🤔 O que são Aliases ?

Alias é basicamente um apelido para um apelido/nome alternativo para uma palavra. O contexto mais comum do uso de aliases são em comandos em shells para agilizar as escritas e interações.

# 🛠️ Como fazer ?

## ⚠️ Pré-requisito
É preciso ter esses dois instalados na sua máquina caso queira usar os comandos do Git.
- [Git](http://git-scm.com/downloads)
- [Git bash](https://www.webdevdrops.com/git-bash-como-instalar-usar/)

---

## 🪟 Windows

Nesse SO você vai precisar acessar a pasta do seu usuário.

Exemplo de path:
```shel
C:\Users\mathe
```

Depois deve procurar o arquivo **.bashrc** e abri-lo em um editor de texto de sua preferência.

Após isso basta usar a seguinte sintaxe para escrever seus aliases.

**Alias simples**
```shell
# Comando para git status -> comentario

alias gs='git status'
```

**Alias Composto (com dois comandos)**
```shell
# Comando para git add + git commit -> comentario

alias gc='git add . && git commit -m '
```
Exemplo de uso: 

Usando alias para fazer um commit.
``` shell
gc "Initial commit"
```
Com isso será executado o comando **git add** e depois o **git commit -m**, após isso vem a mensagem do commit.

Os alias podem ser usados para qualquer comando que seja executável no terminal do seu sistema, então é possível criar aliases para os mais diversos usos.

## 🤖 Linux

Para utilizar os aliases disponíveis no arquivo .bashrc aqui disponível, após clonar o repositório, utilize o comando aseguir a partir da home do seu usuário

```
cat <diretório>/git-aliases/.bashrc >> .bashrc
```

# 🤓 Meu bashrc
Aqui nesse repositório você vai encontrar o meu arquivo **.bashrc**, para usa-lo basta você substituir o seu bashrc pelo o meu e reiniciar o terminal (famoso fechar e abrir de novo).

## 🤔 Quais aliases uso?
Os alias que utilizo foram feitos para atender as minhas necessidades durante o desenvolvimento, fique à vontade para adequa-los às suas.

Para ficar mais simples, dividi os alias em categorias, são elas:

- WSL
- Git
- Acesso à alguns diretórios
- Docker
- Docker-compose


## 👨🏻‍💻 Autor

<br>
<a href="https://github.com/matheuscarv69">
 <img style="border-radius: 35%;" src="https://avatars1.githubusercontent.com/u/55814214?s=460&u=ffb1e928527a55f53df6e0d323c2fd7ba92fe0c3&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Matheus Carvalho</b></sub></a> <a href="https://github.com/matheuscarv69" title="Matheus Carvalho">🚀</a>

Feito por Matheus Carvalho, entre em contato!✌🏻
 <p align="left">
    <a href="mailto:matheus9126@gmail.com" alt="Gmail" target="_blank">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:matheus9126@gmail.com"/></a>
    <a href="https://www.linkedin.com/in/matheus-carvalho69/" alt="Linkedin" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/matheus-carvalho69/"/></a>  
    <a href="https://www.instagram.com/_mmcarvalho/" alt="Instagram" target="_blank">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&link=https://www.instagram.com/_mmcarvalho/"/></a>  
  </p>


