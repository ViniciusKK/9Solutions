# 9Solutions AI Chat

Este projeto é uma aplicação de chat com IA baseada em React que utiliza o modelo GPT da OpenAI para fornecer respostas inteligentes.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado:
- Node.js (versão 12.0 ou superior)
- npm (geralmente vem com o Node.js)

## Instalação

1. Clone o repositório:
   ```
   git clone https://github.com/seu-usuario/9solutions-chat.git
   cd 9solutions-chat
   ```

2. Instale as dependências:
   ```
   npm install
   ```

3. Instale o pacote adicional necessário:
   ```
   npm install axios
   ```

## Configuração do Ambiente

1. Crie um arquivo `.env` no diretório raiz do projeto.
2. Adicione sua chave de API da OpenAI ao arquivo `.env`:
   ```
   REACT_APP_OPENAI_API_KEY=sua_chave_api_aqui
   ```
   Substitua `sua_chave_api_aqui` pela sua chave de API real da OpenAI.

Nota: Nunca cometa o arquivo `.env` para o controle de versão. Ele já está incluído no `.gitignore`.

## Executando a Aplicação

Para iniciar o servidor de desenvolvimento:
