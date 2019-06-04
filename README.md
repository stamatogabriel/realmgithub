<!-- TABLE OF CONTENTS -->

## Tabela de Conteúdo

- [Tabela de Conteúdo](#tabela-de-conte%C3%BAdo)
- [Sobre o Projeto](#sobre-o-projeto)
  - [Feito Com](#feito-com)
- [Começando](#come%C3%A7ando)
  - [Pré-requisitos](#pr%C3%A9-requisitos)
  - [Instalação](#instala%C3%A7%C3%A3o)
- [```](#)
  - [Como funciona o aplicativo](#como-funciona-o-aplicativo)
- [Licença](#licen%C3%A7a)
- [Contato](#contato)

<!-- ABOUT THE PROJECT -->

## Sobre o Projeto

Este projeto visa o estudo de React Native juntamente com RealmDB para a criação de aplicações com banco de dados locais.

### Feito Com

- [React Native](http://facebook.github.io/react-native/) - O React Native é um framework que permite o desenvolvimento de aplicações mobile usando Javascript e React;
- [React Navigation](https://reactnavigation.org/) - O React Navigation surgiu da necessidade comunidade do React Native de uma navegação de forma fácil de se usar, e escrita toda em Javascript;
- [React Native Gesture Handler](https://kmagiera.github.io/react-native-gesture-handler/) - API declarativa que permite a manipulação de toques e gestos no React Native;
- [Axios](https://github.com/axios/axios) - O Axios é um cliente HTTP baseado em Promises para Browser e NodeJS;
- [Prop Types](https://github.com/facebook/prop-types) - Verificação de tipo em tempo de execução para propriedades (props) React e objetos semelhantes;
- [Reactotron](https://github.com/infinitered/reactotron) - O Reactotron é um app Desktop para inspecionar projetos em React ou React Native. Está disponível para macOS, Linux e Windows;
  - [reactotron-react-native](https://github.com/infinitered/reactotron/blob/master/docs/quick-start-react-native.md) - Plugin para configurar o Reactotron para se conectar ao projeto React Native;
- [Babel](https://babeljs.io/) - O Babel é um compilador JavaScript gratuito e de código aberto e transpiler configurável usado no desenvolvimento de aplicações Javascript;
  - [babel-eslint](https://github.com/babel/babel-eslint) - Este pacote é um _wrapper_ do parser do Babel para o ESLint;
  - [babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) - Esse plugin do Babel permite que sejam feitos imports e requires em caminhos baseados em uma raiz(root);
- [Eslint](https://eslint.org/) - O ESLint é uma ferramenta de lint plugável para JavaScript e JSX;
  - [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Este pacote fornece o .eslintrc do Airbnb como uma configuração compartilhada extensível;
  - [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) - Plugin do ESLint com regras para ajudar na validação de imports;
  - [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Verificador estático AST das regras do a11y em elementos JSX;
  - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) - Regras de linting do ESLint específicas do React;
  - [eslint-plugin-react-native](https://github.com/Intellicode/eslint-plugin-react-native) - Regras de linting do ESLint específicas do React Native;
  - [eslint-import-resolver-babel-plugin-root-import](https://github.com/olalonde/eslint-import-resolver-babel-root-import) - Um resolver da lib _babel-root-import_ para a lib _eslint-plugin-import_;
- [EditorConfig](https://editorconfig.org/) - O EditorConfig é um formatador de arquivos e coleções em forma de Plugin para Editores de código/texto com o objetivo de manter um padrão de código consistente entre diferentes editores, IDE's ou ambientes;
- [RealmDB](https://realm.io/) - É um banco de dados orientado a objetos criado especificamente para mobile. Funciona como substituto para SQLite no Android e Core Data no iOS.

## Começando
Para conseguir utilizar o projeto, crie uma cópia local dos arquivos e siga os passos abaixo.

### Pré-requisitos

Antes de seguirmos, é ideal que você tenha o ambiente configurado para criar e testar aplicativos em React Native. Segue um link abaixo do pessoal da [Rocketseat](https://rocketseat.com.br/) com um passo a passo bem explicativo:

[Ambiente React Native (Android/iOS)](https://github.com/Rocketseat/ambiente-react-native)

### Instalação

1. Para instalar e utilizar esse projeto o processo é bem simples. Abra um terminal no diretório do projeto e digite:

```sh
npm install
```
ou
```sh
yarn
```

Isso instalará todas as dependencias necessárias para que você possa rodar o projeto localmente.

2. Abra o emulador de sua preferência e digite no terminal:

Para emuladores Android:
   ```sh
react-native run-android
```

Para emuladores IOS:
```sh
react-native run-ios
```
---
### Como funciona o aplicativo

Logo na tela principal, o usuário terá uma caixa de texto onde digitará o nome do repositório e o mesmo será salvo no banco de dados e será mostrado na tela principal, juntamente com os repositórios salvos anteriormente.

A listagem exibida na tela principal será pela qntidade de **stars** que o repositório tiver no [Github](https://github.com).

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Contato

Gabriel Stamato - [Github](https://github.com/stamatogabriel) - **stamato7@gmail.com**
