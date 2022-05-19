Este projeto contém os requisitos realizados por _[Anna Beatriz Garcia Trajano de Sá](www.linkedin.com/in/anna-beatriz-trajano-de-sá)_ enquanto estudava na [Trybe](https://www.betrybe.com/) :rocket:

# Project Docker To do List

Neste projeto pude fixar o conceitos e comandos relacionados aos Docker (manipulação de containers e imagens) e também foi possível entender, de 
forma introdutória, a comunicação entre serviços, nesse caso, o front-end e back-end!

Para isto, utilizei uma série de comandos do Docker com diferentes níveis de complexidade.

Além disso, temos uma aplicação full-stack neste repositório: um aplicativo de tarefas!

Veja o exemplo a seguir do layout do projeto!

## Demo e Layout

Search Page             |         
:-------------------------:|
![Screeshot](img/screen_1.png)  |

 
## Instalação do projeto localmente:
 
Após cada um dos passos, haverá um exemplo do comando a ser digitado para fazer o que está sendo pedido, caso tenha dificuldades e o exemplo não seja suficiente, não hesite em me contatar em _annagarcia@id.uff.br_ 

1. Abra o terminal e crie um diretório no local de sua preferência com o comando **mkdir**:
```javascript
  mkdir projetos
```

2. Entre no diretório que acabou de criar e depois clone o projeto:
```javascript
  cd projetos
  git clone git@github.com:annabia95/project-docker-todo-list.git
```

3. Acesse o diretório do projeto e depois utilize o comando **npm i** na pasta de back-end e front-end para instalar todas as dependências necessárias:
```javascript
  cd project-docker-todo-list
  npm i
```

4. Por último, rode o comando **npm start** na pasta de back-end e front-end e acesse o projeto via browser, no caminho `http://localhost:3000/project-docker-todo-list`.

```javascript
  npm start
```

## Habilidades Desenvolvidas

Neste projeto, desenvolvi as seguintes habilidades:

 - Conteinerizar aplicações, com o Docker;
 - Criar uma conexão entre elas (front-end, back-end e testes);
 - Orquestrar seu funcionamento, com docker-compose.
 
 ## Referências
 
 [Documentação oficial do Docker - Docker images](https://docs.docker.com/engine/reference/run/)<br>
 [Documentação oficial do Docker - Dockerfile](https://docs.docker.com/engine/reference/builder/)<br>
 [Docker Compose na prática (Fácil)](https://youtu.be/HxPz3eLnXZk)<br>
 [Docker em 22 minutos - teoria e prática (Rápido!)](https://youtu.be/Kzcz-EVKBEQ)<br>
 
 
 ## Escopo do Projeto
 
 **Comandos docker
 - Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12;
 - Inicie o container 01container;
 - Liste os containers filtrando pelo nome 01container;
 - Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele;
 - Remova o container 01container;
 - Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container;
 - Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro;
 - Pare o container 02images que está em andamento
 
 **Dockerfile
  - Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend;
  - Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend;
  - Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests;
 
 **Docker-compose
  - Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar.

 
