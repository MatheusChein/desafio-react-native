
<h2 align="center">
  Desafio 03 Bootcamp GoStack - Conceitos do React Native ✍️ <hr >
  <img width="500" src="https://miro.medium.com/max/3840/1*QDQvlCg420lzRElCK4AYhw.png">
</h2>

## :rocket: Sobre o desafio

Objetivo do desafio: criar uma aplicação para armazenar repositórios fictícios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

Front-end mobile feito em React Native, utilizando a API construída em Node nesse <a href="https://github.com/MatheusChein/desafio-node">repositório</a>

Desafio original: https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-react-native

## Funcionalidades da aplicação

- **`Listar os repositórios da API`**

- **`Curtir um repositório listado da API`**

- **`Adicionar um repositório à API`** <em>em breve...</em>

- **`Remover um repositório da API`**

<h2>:toolbox: Tecnologias usadas</h2>
<ul>
<li>React Native;</li>
<li>Javascript;</li>
</ul>

<h2>:man_technologist: Features</h2>
<ul>
<li>Componentização</li>
<li>Imutabilidade e mudanças de estado</li>
<li>Requisições HTTP</li>
<li>Desestruturação ES6</li>
<li>Funções Assíncronas</li>
</ul>

<h2>:heavy_check_mark: Rode o Front-end na sua máquina</h2>
Clonar o <a href="https://github.com/MatheusChein/desafio-node">repositório</a> com a API em Node e seguir as instruções de lá
<br>
$ git clone https://github.com/MatheusChein/desafio-react-native.git
<br>
$ yarn
<br>
$ npx react-native start (somente se estiver no Linux)
<br>
Dependendo de onde for rodar, emulador ou dispositivo físico, é preciso alterar ou não a baseURL do arquivo src/services/api de acordo com as instruções
<ul>
<li>iOS com emulador: localhost</li>
<li>iOS com dispositivo físico: IP da máquina</li>
<li>Android com Emulador: localhost (precisa ir no terminal e digitar $ adb reverse tcp:3333 tcp:3333) </li>
<li>Android com Emulador: 10.0.2.2 (Android Studio)</li>
<li>Android com Emulador: 10.0.3.2 (Genymotion)</li>
<li>Android com dispositivo físico: IP da máquina</li>
</ul>
$ npx react-native run-android (para Android)
<br>
$ npx react-native run-ios (para iOS)
<br>
<hr>
💼 <a href="https://www.linkedin.com/in/matheus-chein/">Matheus Chein</a>
