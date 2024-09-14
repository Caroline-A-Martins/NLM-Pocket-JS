# App de Metas

Este é um aplicativo interativo de linha de comando (CLI) para gerenciamento de metas, executado via terminal. Ele permite que os usuários cadastrem, visualizem, marquem como concluídas, listem metas abertas, e até mesmo deletem metas. As metas são armazenadas localmente em um arquivo `metas.json`, para que possam ser carregadas e salvas automaticamente.

## Funcionalidades

- **Cadastrar Meta**: Permite ao usuário adicionar novas metas, verificando se a meta já foi cadastrada anteriormente para evitar duplicatas.
- **Listar Metas**: Exibe todas as metas e permite marcar ou desmarcar metas como concluídas.
- **Metas Realizadas**: Exibe a quantidade e os detalhes das metas concluídas.
- **Metas Abertas**: Mostra a quantidade e os detalhes das metas que ainda não foram concluídas.
- **Deletar Metas**: Permite que o usuário selecione e delete metas do sistema.
- **Armazenamento Local**: As metas são salvas em um arquivo JSON para persistência de dados entre sessões.

## Instalação

1. Clone este repositório.   
2. Navegue até o diretório do projeto.   
3. Instale as dependências.   
   
## Como usar
1. Execute o aplicativo de metas via terminal:
   ```bash
   node app.js
 2. Navegue pelo menu interativo no terminal para realizar as seguintes ações: 
- **Cadastrar Meta**: Adicione uma nova meta. O sistema verifica se a meta já existe para evitar duplicidade.
- **Listar Metas**: Visualize suas metas e marque como concluídas.
- **Metas Realizadas**: Veja o progresso com as metas concluídas.
- **Metas Abertas**: Veja as metas que ainda precisam ser realizadas.
- **Deletar Metas**: Exclua metas específicas do sistema.
- **Sair**: Encerre o aplicativo.

## Tecnologias Utilizadas
 - **Node.js**: Plataforma de desenvolvimento para executar JavaScript no servidor.
 - **Inquirer**: Biblioteca usada para criar prompts interativos no terminal.
 - **File System (fs)**: Módulo nativo do Node.js para manipulação de arquivos JSON.

## Estrutura
  - **app.js**: Arquivo principal que contém a lógica do aplicativo.
  - **metas.json**: Armazena as metas cadastradas, concluídas ou abertas.
  - **package.json**: Contém as dependências e scripts do projeto.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar **issues** e **pull requests**.

1. **Fork** este repositório.
2. Crie uma nova branch.
3. Faça commit de suas alterações.
4. Push para a branch.
5. Abra um Pull Request.
 



