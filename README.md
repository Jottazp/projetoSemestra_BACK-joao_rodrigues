# Backend do Blog para atividade de PW3

Este é um projeto de blog desenvolvido com **React.js** no frontend, **Node.js**, **Express** e **MongoDB** no backend, focado em proporcionar uma plataforma para publicação, gerenciamento e interação com artigos. O projeto inclui um sistema de login com autenticação de usuários e um CRUD completo para postagens.

## Funcionalidades

- **Sistema de Login**: Implementação de autenticação de usuários, com controle de sessões e gerenciamento de credenciais.
- **CRUD de Postagens**: Criação, leitura, atualização e exclusão de postagens, com suporte para upload de imagens e edição de conteúdo em formato de texto.

## Implementações futuras

- **Editor de Texto Rico**: Ferramenta para escrever e formatar os artigos de forma prática e interativa.
- **Organização por Categorias e Tags**: Artigos podem ser categorizados e etiquetados para facilitar a busca e organização.
- **Sistema de Comentários**: Os leitores podem comentar nas postagens e interagir com os conteúdos.
- **Sistema de Reações**: Os usuários podem reagir às postagens, permitindo feedback imediato.
- **Controle de Acesso**: Diferentes níveis de acesso para administradores e autores.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/Jottazp/projetoSemestral_BACK-joao_rodrigues.git

2. Instale as dependências:
   ```bash
   npm install

3. Crie o arquivo .env na raiz do projeto, digite CONNECT_URL = "" e coloque seu link com usuário e senha do cluster do Atlas MongoDB dento das aspas:
   CONNECT_URL = "mongodb+srv://user:password@cluster0.5w45j.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm start