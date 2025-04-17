# 💸 App de Controle de Saldo

Este é um projeto simples desenvolvido em **React Native** utilizando **Expo Go**, com foco no aprendizado de componentes, estado e contexto. A aplicação permite **adicionar e subtrair valores** de um saldo exibido na tela.

## 📱 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- Context API (React)

## 🎯 Funcionalidades

- Exibir o saldo atual
- Inserir valores via campo de texto
- Botões para adicionar ou subtrair do saldo
- Gerenciamento de estado com `useContext` e `useState`

## 🧠 O que foi aprendido

- Criação e uso de **componentes funcionais**
- Gerenciamento de estado com **useState**
- Compartilhamento de estado global com **Context API**
- Estilização com **StyleSheet** do React Native

## 📂 Estrutura do Projeto

### 🔹 App.js

Arquivo principal que importa os componentes e fornece o contexto via `SaldoProvider`.

### 🔹 componentes/Saldo.js

Componente responsável por **exibir o saldo atual** do usuário.

### 🔹 componentes/Lancamento.js

Componente com um `TextInput` para digitar um valor e um botão que **adiciona ou subtrai** do saldo, dependendo da `props.Credito`.

### 🔹 context/ContaContext.js

Implementação do **Context API** que fornece o estado `saldo` para todos os componentes filhos.
