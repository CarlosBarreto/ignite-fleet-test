<div align="center">
  <h1 style={{ margin: 0 }}>Ignite Fleet</h1>
  <p style={{ marginTop: 0 }}>
    Projeto desenvolvido durante o curso Ignite da Rocketseat.
  </p>
  <img src="assets/illustration.png" alt="Ignite Fleet" />
</div>

## 📝 Sobre

O Ignite Fleet é um aplicativo que facilita a gestão de viagens. Os usuários podem criar uma conta com o Google, cadastrar veículos pela placa com descrição, estabelecer trajetos de saída e chegada, e registrar o histórico completo das viagens para referência posterior.

### 🔖 Funcionalidades

- [x] Autenticação com o Google
- [x] Cadastro de viagens
- [x] Armazenamento de dados no dispositivo
- [x] Armazenamento de dados na nuvem
- [x] Execução de tarefas em background
- [x] Exibição de mapa com trajetos
- [x] Exibição de histórico de viagens

### 🎨 Layout

O layout do aplicativo foi desenvolvido pela equipe da Rocketseat e pode ser acessado através do link abaixo:

- [Layout do Figma](https://www.figma.com/community/file/1233747170984378974)


## 🚀 Tecnologias

- [React Native](https://reactnative.dev/) - Framework para desenvolvimento de aplicativos nativos para Android e iOS.
- [Expo](https://expo.io/) - Plataforma para desenvolvimento de aplicativos nativos com React Native.
- [Expo-location](https://docs.expo.io/versions/latest/sdk/location/) - Biblioteca para obtenção de localização do dispositivo.
- [Expo-task-manager](https://docs.expo.io/versions/latest/sdk/task-manager/) - Biblioteca para execução de tarefas em background.
- [TypeScript](https://www.typescriptlang.org/) - Superset JavaScript que adiciona tipagem estática à linguagem.
- [Styled Components](https://styled-components.com/) - Biblioteca para estilização de componentes.
- [React Navigation](https://reactnavigation.org/) - Biblioteca para navegação entre telas.
- [Async Storage](https://react-native-async-storage.github.io/async-storage/) - Biblioteca para armazenamento de dados no dispositivo.
- [Realm](https://realm.io/) - Banco de dados online para armazenamento de dados.
- [Google Sign-In](https://developers.google.com/identity/sign-in/web/sign-in) - Biblioteca para autenticação com o Google.

Entre outras bibliotecas, consulte o arquivo [package.json](package.json) para mais detalhes.

## 📦 Instalação

### 🚧 Pré-requisitos

Por ser um aplicativo desenvolvido com React Native e Expo, é necessário ter instalado em sua máquina o [Node.js](https://nodejs.org/en/) e o [Expo CLI](https://docs.expo.io/get-started/installation/). Além disso, é necessário ter um dispositivo físico ou um emulador Android ou iOS para executar o aplicativo. Para mais informações sobre como configurar o ambiente de desenvolvimento, consulte a [documentação do React Native](https://reactnative.dev/docs/environment-setup).

### 🔧 Instalação

```bash
# Clone o repositório
$ git clone

# Entre na pasta do projeto
$ cd ignite-fleet

# Instale as dependências
$ yarn install

# Faça uma cópia do arquivo .env.example e preencha com as suas credenciais do Google Sign-In
$ cp .env.example .env

# Inicie o servidor de desenvolvimento
$ yarn start
```


## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### 🖊️ Autor - [@raniellimontagna](https://www.github.com/raniellimontagna)
