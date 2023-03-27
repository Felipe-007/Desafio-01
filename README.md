<h1 align="center">
  to.do
</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033">

 <img src="https://img.shields.io/static/v1?label=NLW&message=06&color=E51C44&labelColor=0A1033" alt="NLW 06" />
</p>

# 💻 Desafio 01 - Conceitos do React Native
Aplicativo desenvolvido em React Native, utilizando CLI.

## Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no React Native.

Essa será uma aplicação de lembrete de tarefas, onde você vai treinar um pouco mais sobre manipulação do estado no React.
As funcionalidades do aplicativo são:

- Contagem de tarefas;
- Adicionar uma nova tarefa;
- Remover uma tarefa;
- Marcar e desmarcar uma tarefa como concluída.
- Edição de uma tarefa;
- Exibir alerta pedindo confirmação ao remover uma tarefa;
- Exibir alerta ao tentar adicionar tarefa com o mesmo nome.

## ✨ Tecnologias

-   [ ] React Native 
-   [ ] CLI
-   [ ] TypeScript

## 🔖 Executando o projeto

Utilize o **yarn** ou o **npm install** para instalar as dependências do projeto.
Em seguida, inicie o projeto.

```cl
git clone https://github.com/Felipe-007/Desafio-01.git
cd Desafio-01
npm i
npx react-native run-android
```
## Possíveis erros:
```bash
Caso apresente o erro:
# opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
# library: 'digital envelope routines',
# reason: 'unsupported',
# code: 'ERR_OSSL_EVP_UNSUPPORTED'

Execute o comando:
set NODE_OPTIONS=--openssl-legacy-provider && npm run start
```

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

<br />

<div align="center">
  <small>Agradecimentos ao professor Rodrigo Gonçalves</small>  
</div>

<br />

![cover](.github/cover.png?style=flat)