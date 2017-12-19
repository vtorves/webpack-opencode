# Webpack Opencode Workflow [WOW]

Workflow desenvolvido para trabalhar com lojas Tray utilizando o Opencode
Suporte a ES6+ features

### Requisitos

Antes de começar é necessário ter instalado:

* NodeJS
* Ruby 2.3
* Terminal Linux

### Instalação

Após instalado os requisitos abra o terminal, navegue até a pasta e instale as dependências

```
npm install
```

Para iniciar o workflow rode

```
npm run opencode
```

Este comando faz com que o Node inicie os processos do Webpack
Mas ainda precisamos rodar o watch no Opencode para subir os arquivos
Então em outro terminal, entre na pasta /dist e rode

```
opencode watch
```

Pronto! Seu ambiente está pronto para desenvolver :]

### Entendendo a estrutura

```Workflow
├── dist
│   ├── css
│   │   ├── **/*.css
│   ├── js
│   │   ├── **/*.js
│   ├── img
│   │   ├── **/*.jpg|png|svg
│   └── layouts
│       ├── default.html
│   └── elements
│       ├── snippets
│   └── pages
│   └── configs
│   ├── config.yml
├── node_modules
├── src
│   ├── js
│   │   ├── **/*.js
│   ├── scss
│   │   ├── **/*.scss
│   └── index.js
├── .gitignore
├── README.md
├── package.json
├── webpack.config.js
└── .gitignore
```

## Construído com

* [Webpack](https://webpack.js.org/) - Module Bundler
* [Opencode](http://dev.tray.com.br/frontend/console-tool/) - Gem do Ruby
* [Node](https://nodejs.org/en/) - Gerenciador de dependências

## Contribuindo

Por favor leia [CONTRIBUTING.md](https://github.com/linconkusunoki/webpack-opencode/CONTRIBUTING.md) para detalhes da nossa conduta de código, e o processo para enviar um pull request.

## Authors

* **Lincon Kusunoki** - *Front-end* - [Tray](https://github.com/tray-tecnologia/)

## Licença

Este projeto está licenciado sub a licença MIT - veja [LICENSE.md](LICENSE.md) para mais detalhes
