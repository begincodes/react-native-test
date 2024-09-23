# Instruções para Realização do Teste Prático

### Execute o projeto localmente

O código fornecido precisa ser configurado e executado corretamente para que você possa desenvolvê-lo posteriormente.

O Expo mostrará alguns erros quando você tentar executá-lo em um emulador ou dispositivo, corrigir esses erros fazem parte do teste. Depois de corrigi-los, o aplicativo será executado sem qualquer mensagem de erro ou aviso.

### Tasks

**React Native (Frontend)**
* Atualize a versão do EXPO para a última versão disponível: [Expo Docs](https://docs.expo.dev/workflow/upgrading-expo-sdk-walkthrough/)
* Corrija o posicionamento do botão "Done/Undone", o mesmo deve ficar posicionado ao lado direito do texto, não abaixo como está sendo apresentado.
* A largura da lista de tarefas está ocupando uma parte muito pequena da tela, além de estar posicionada ao centro. Altere para que a lista ocupe 90% da tela e seja posicionada na parte superior da tela.
* Ao adicionar muitos itens, a lista acaba ficando muito comprida, fazendo com que alguns itens fiquem além da área visível. Adicione um scroll para que isso não ocorra mais.
* Construa o aplicativo para o Android no formato .apk.

**C# (.NET Core - Backend)**
* Crie um CRUD em C# utilizando .NET Core e APIs para gerenciar os dados da lista de TODO.
* O projeto deve ser entregue em dois repositórios Git criados por você com os nomes: `todolist-app` e `todolist-api`.
* O APK deve estar consumindo a API, que deve ser hospedada no Free Tier da Azure.
* O banco de dados utilizado deve ser SQL. Se necessário, solicite a criação de uma instância do banco de dados no SQL.

_Qualquer melhoria de layout ou performance é bem-vinda, fique livre para realizar quaisquer outras alterações. Caso não consiga realizar algumas das tasks, explique o motivo ao final deste arquivo (README.md) para que possamos entender o que ocorreu._

### Entrega

Adicione o .apk na raiz do projeto.

Faça uma cópia deste projeto para sua conta pessoal do GitHub ou Bitbucket, adicione suas alterações, faça o commit e push do código com todas as alterações.

# README #

Este projeto foi construído usando Expo, toda a documentação pode ser encontrada em [Expo Docs].

[Expo Docs]: https://docs.expo.io

## Requisitos

* Node - [Node](https://nodejs.org/en/)
* Expo-Cli - `npm install -g expo-cli`
* Yarn - [Download](https://classic.yarnpkg.com/en/docs/install/#windows-stable)

## Início Rápido

* Execute `yarn`
* Inicie com `yarn start`

### Abrindo o app no seu telefone/tablet

> 👨 Você pode abrir o projeto em vários dispositivos simultaneamente. Vá em frente e experimente em um iPhone e em um telefone Android ao mesmo tempo, se você tiver ambos à mão.

* 🍎 No seu iPhone ou iPad, abra o aplicativo padrão "Câmera" da Apple e escaneie o código QR que você vê no terminal ou no Expo Dev Tools.
* 🤖 No seu dispositivo Android, pressione "Scan QR Code" na aba "Projects" do aplicativo cliente Expo e escaneie o código QR que você vê no terminal ou no Expo Dev Tools.
