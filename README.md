# Labenu | Desenvolvimento Web Full Stack


<p align="center">
  <img src="https://user-images.githubusercontent.com/59856574/86274338-e7bbd280-bba7-11ea-9b0f-312418c0c364.png"/>
</p>

## Frontend do Projeto Spotenu

<p align="center">
  <img src="https://user-images.githubusercontent.com/59856574/86313495-9f2e0480-bbfb-11ea-9163-5c5e570cf8c1.PNG"/>
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=firebase&message=deploy&color=yellow&style=for-the-badge&logo=FIREBASE"/>
  <img src="https://img.shields.io/static/v1?label=redux&message=library&color=purple&style=for-the-badge&logo=REDUX"/>
  <img src="https://img.shields.io/static/v1?label=javascript&message=language&color=yellow&style=for-the-badge&logo=JAVASCRIPT"/>
  <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
  <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
</p>

> Status do Projeto: Em desenvolvimento :warning: 

## Descrição do Projeto

<p align="justify"> 
  Vamos finalizar o curso com chave de ouro fazendo o frontend para simular o Spotify. 
</p>
<p align="justify"> 
  O Spotenu é um projeto que visa facilitar o acesso a músicas pelo mundo. Para isso, vamos dar suporte para dois tipos de usuários: as bandas (ou músicos) e os ouvintes (usuários que consomem as músicas).
  Além disso, nós vamos montar uma operação com funcionários próprios que precisam gerenciar os dados que circulam no nosso sistema. Eles serão os nossos administradores. 
</p>

#### Usuários Músicos
<p align="justify">
  Vamos começar a explicar os usuários que são uma banda. Mesmo que haja músicos solos, nós vamos representar todos eles por uma banda, que deve possuir um nome, um nickname, uma descrição (onde se possa escrever qualquer texto de qualquer tamanho) e uma senha. 
  Quando uma banda de cadastra, ela precisa esperar que um administrador aprove o seu cadastro para pode utilizar a nossa aplicação. 
</p>
<p align="justify">
  As funcionalidades relacionadas a músicos são: criação, edição e deleção de álbuns; e criação, edição e deleção de músicas. Para criar um álbum, devemos informar o nome e relacioná-lo com um conjunto de gêneros. Um álbum pode ser de mais de um gênero musical. Na edição, é possível alterar o nome do álbum e os gêneros dele. Para criar uma música, os músicos devem informar o nome da música e o álbum a qual ela está relacionada.
Só é possível alterar o nome da música. Por fim, sobre a deleção de músicas, não há muito o que explicar, mas a de álbuns tem um comportamento importante: ao se deletar um álbum todas as músicas devem ser deletadas também.  
</p>
<p align="justify">
Para se logar, o usuário músico pode fornecer o email ou o nickname (junto com a senha). Caso ele não tenha sido aprovado ainda, ele não deve ser capaz de se logar na aplicação.
</p>

#### Usuários Ouvintes
<p align="justify">
  Os ouvintes são divididos em duas categorias: pagantes e não pagantes. 
  Os não pagantes só podem acessar a funcionalidade de busca da música, que deve fazer uma busca por termos dos nomes das músicas, com filtro de gênero opcional.
</p>
<p align="justify">
  Já os pagantes tem acesso a isso e mais: playlists próprias. Ao criar uma playlist, basta fornecer um nome. Podem ser adicionadas músicas da playlist, ou retira-las. 
  Todas as playlist são inicialmente privadas e só podem ser modificadas (ou adicionar e retirar músicas) pelo usuário criador. 
  Ele pode tornar a playlist colaborativa, permitindo que qualquer um a veja; e, então, quem for seguidor da playlist também pode a modificar.
</p>
<p align="justify">
  Um usuário ouvinte deve fornecer o nome, o email, nickname e senha no cadastro. Para logar, ele pode usar tanto o email como o nickname (junto com a senha).  
</p>

#### Usuários Administradores 

<p align="justify">
  Os usuários administradores são responsáveis pelo gerenciamento do nosso projeto. 
  Somente um usuário administrador pode cadastrar outro usuário administrador, passando as informações: nome, email, nickname e senha. 
</p>
<p align="justify">
  Eles podem aprovar os músicos (como explicado acima). Além disso, eles também são capazes de adicionar gêneros musicais, passando somente um nome.
</p>
<p align="justify">
  Por fim, há a possibilidade de bloquear qualquer usuário (que não seja um administrador). 
  Quando um usuário for bloqueado ele não pode mais logar na aplicação. 
  Para se logar, um administrador pode informar o email ou o nickname (junto com a senha)
</p>

## Funcionalidades

- Signup de usuário ouvinte
- Signup de bandas
- Cadastro de administrador
- Ver todas as bandas 
- Aprovação de bandas
- Login
- Adicionar Gênero
- Ver gêneros músicias
- Criação de álbuns
- Criação de músicas

## Deploy

<p align="justify">
  O deploy do projeto foi realizado no firebase e encontra-se disponivel em: https://spotenu-dd294.web.app/
</p>

## Pré-requisitos

:warning: [Node](https://nodejs.org/en/download/)

:warning: [Npm](https://www.npmjs.com/)

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto: 

```
git clone https://github.com/nauaramelo/spotenu-front.git
```
Entre no projeto e instale as dependências através do comando:
```
npm install
```
Por últomo, suba a aplicação: 
```
npm start
```

## Linguagens, dependencias e libs utilizadas :books:

- [Node](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [Redux](https://redux.js.org/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://alligator.io/react/axios-react/)
- [Material ui](https://material-ui.com/pt/)
- [Firebase](https://firebase.google.com/)

## Desenvolvido Por :octocat:

| [<img src="https://user-images.githubusercontent.com/59856574/86283681-d11d7780-bbb7-11ea-90a5-9312ee67cdec.jpg" width=115><br><sub>Nauara Melo</sub>](https://www.linkedin.com/in/nauara-melo-mayer-464a82135/) | 
| :---: |

## Licença 

[MIT License](https://github.com/nauaramelo/spotenu-front/blob/master/LICENSE)

Copyright :copyright: 2020 - Spotenu
