<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/Matheus-Chaves/desafio-ignite-react-02.svg)](https://github.com/Matheus-Chaves/desafio-ignite-react-02/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Matheus-Chaves/desafio-ignite-react-02.svg)](https://github.com/Matheus-Chaves/desafio-ignite-react-02/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
  <img  src="/.github/banner.png" alt="Project logo"><br>
  <span>
    WatchMe - Segundo desafio das aulas de ReactJS do curso Ignite, da <a href="https://rocketseat.com.br/">Rocketseat</a>.
  </span>
</p>

## 📝 Sumário

- [Sobre](#sobre)
- [Iniciando o projeto](#getting_started)
- [Rodando os testes](#tests)
- [Utilização](#utilizacao)
- [Construído com](#construido_com)
- [Autores](#autores)

## 🧐 Sobre <a name = "sobre"></a>

O :sparkles: **WatchMe** :sparkles: é uma aplicação React que exibe informações sobre alguns filmes de diversas categorias através da leitura de um arquivo `.json`, simulando o consumo de uma API (Fake API com JSON Server).

É um desafio inteiramente Front-End, que foi desenvolvido através das aulas de ReactJS do curso Ignite, da [Rocketseat](https://rocketseat.com.br/).

### 💭 Como passar no desafio?

O projeto já está funcional, porém o arquivo `App.tsx` possui muito código dentro dele - muita responsabilidade dentro de um só componente é um problema ❌.

Logo, para passar neste desafio, foi necessário refatorar o que foi feito através da criação de dois componentes: `Content.tsx` (responsável pelo local onde aparece o conteúdo dos filmes) e `SideBar.tsx` (responsável por mostrar o título e pela navegação no site).

## 🏁 Iniciando o projeto <a name = "getting_started"></a>

As instruções abaixo irão servir para que o projeto seja corretamente instalado e utilizado em seu dispositivo.

### Pré-requisitos

É necessário ter as tecnologias abaixo instaladas em sua máquina para poder seguir os próximos passos.

- Um navegador para que o sistema rode (Google Chrome, Firefox, Edge, etc.)
- [Node.js](https://nodejs.org/pt-br/)
- [Git](https://git-scm.com/download/windows)
- (Opcional) - Editor de código para edição e visualização do script. Recomendado: [Visual Studio Code](https://code.visualstudio.com/download)

### ⚙️ Instalação e uso

Siga o passo a passo abaixo para instalar corretamente o aplicativo e rodá-lo no seu próprio dispositivo.

Para seguir as instruções abaixo corretamente, abra o terminal do seu sistema operacional e execute os seguintes comandos:

```bash
# Clone o repositório deste projeto
$ git clone https://github.com/Matheus-Chaves/desafio-ignite-react-02.git

# Acesse a pasta do projeto pelo terminal
$ cd desafio-ignite-react-02

# Instale as dependências
$ yarn

# Execute o servidor json-server
$ yarn server

# O servidor rodará na porta:3333, mas não é necessário acessá-la no navegador
# http://localhost:3333/genres
# http://localhost:3333/movies

# Execute a aplicação no modo de desenvolvimento
$ yarn dev

# A aplicação rodará na porta:8080 - acesse <http://localhost:8080>
```

Após as instruções acima, o sistema já poderá ser utilizado.
Caso deseje encerrar/parar a aplicação e/ou o servidor, basta fechar o terminal ou encerrar o comando utilizando `Ctrl + C`.

## 🎈 Utilização <a name="utilizacao"></a>

A utilização do sistema é simples e a interface é bem intuitiva.

### 🎬 Visualizando os filmes

- A categoria do filme está na parte de cima da página
- As informações dos filmes (foto, título, avaliações e duração) estão localizadas na parte direita da página

### 🎥 Escolhendo uma categoria nova

- Na esquerda, clique em uma das categorias disponíveis: ação, comédia, documentário, drama, terror ou família
- O campo ficará destacado, indicando que está selecionado
- O conteúdo na parte direita da página irá mudar, atualizando os filmes de acordo com a nova categoria

<div align="center">
  <img src="/.github/home.png" alt="Tela inicial"/>
  <img src="/.github/demo.gif" alt="Gif de demonstração do projeto"/>
</div>

## ⛏️ Construído com <a name = "construido_com"></a>

- [TypeScript](https://www.typescriptlang.org/) - Linguagem de programação
- [React](https://reactjs.org/) - Biblioteca para desenvolvimento Web
- [Sass](https://sass-lang.com/) - Linguagem de extensão do CSS
- [json-server](https://www.npmjs.com/package/json-server) - Gera uma fake API através de arquivo JSON
- [Axios](https://axios-http.com/ptbr/docs/intro) - Cliente HTTP que trata requisições

## ✍️ Autores <a name = "autores"></a>

- Desafio feito com :heart: by [@matheus-chaves](https://github.com/matheus-chaves)
- Projetado by [Rocketseat](https://rocketseat.com.br/) :purple_heart:
