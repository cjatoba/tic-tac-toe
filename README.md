# Projeto tic-tac-toe de introdução ao React

## Instalação/Configuração inicial

- Instalar a última versão no Node JS, disponível neste link [nodejs](https://nodejs.org/);

- Criar um novo projeto
`npx create-react-app tic-tec-toe`

- Apagar todos os arquivos da pasta src;

- Adicionar um arquivo chamado index.css na pasta src, e nele inserir o conteúdo abaixo:

``````css
body {
    font: 14px "Century Gothic", Futura, sans-serif;
    margin: 20px;
  }
  
  ol, ul {
    padding-left: 30px;
  }
  
  .board-row:after {
    clear: both;
    content: "";
    display: table;
  }
  
  .status {
    margin-bottom: 10px;
  }
  
  .square {
    background: #fff;
    border: 1px solid #999;
    float: left;
    font-size: 24px;
    font-weight: bold;
    line-height: 34px;
    height: 34px;
    margin-right: -1px;
    margin-top: -1px;
    padding: 0;
    text-align: center;
    width: 34px;
  }
  
  .square:focus {
    outline: none;
  }
  
  .kbd-navigation .square:focus {
    background: #ddd;
  }
  
  .game {
    display: flex;
    flex-direction: row;
  }
  
  .game-info {
    margin-left: 20px;
  }
  
``````

- Adicionar um arquivo chamado index.js na pasta src com o conteúdo abaixo:

``````javascript
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
``````



