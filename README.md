📚 Projeto de Automacao Frontend - Serverest

Automacao de testes frontend desenvolvida utilizando Cypress no site Serverest Frontend.

Este projeto cobre cenarios importantes de autenticacao, cadastro de usuarios e busca de produtos.

📝 Casos de Teste Automatizados

Codigo

Descricao

CT001

Login com credenciais invalidas

CT002

Login sem preencher campos obrigatorios

CT003

Cadastro de novo usuario

CT004

Pesquisa de produto

CT005

Login sem preencher campo senha

CT006

Login sem preencher campo usuario

💠 Organizacao do Projeto

📂 cypress
 ├── 📂 e2e           # Casos de teste automatizados
 ├── 📂 fixtures      # Dados de teste (massa de dados)
 ├── 📂 support       # Commands customizados e configuracao global
 └── 📄 config files  # Configuracoes do Cypress
📄 cypress.config.js   # Configuracao principal do projeto
📄 package.json        # Dependencias e scripts do projeto

💻 Requisitos para Rodar o Projeto

Node.js (versao 18.x ou superior)

npm (ja vem com o Node.js)

Cypress (instalado no projeto via dependencia)

👒 Programas que precisam estar instalados

Visual Studio Code (ou seu editor de preferencia)

Git (para clonar o repositorio)

Node.js (obrigatorio para rodar o Cypress)

🚀 Como Instalar e Rodar o Projeto

Clone o repositorio:

git clone https://github.com/andersonfelipe15/serverest-frontend-automation.git

Acesse a pasta do projeto:

cd serverest-frontend-automation

INSTALE AS DEPENDENCIAS:

npm init -y

E DEPOIS RODE:

npm install cypress --save-dev

ABRA O CYPRESS:

npx cypress open

OU, PARA RODAR OS TESTES DIRETAMENTE NO TERMINAL:

npx cypress run

🎯 Tecnologias Utilizadas

Cypress

JavaScript

Node.js

📌 Observacoes

Certifique-se de estar utilizando uma versao estavel do Node.js.

O projeto utiliza Cypress E2E Testing com organizacao modular para facilitar a manutencao e expansao dos testes.

Todos os testes foram desenvolvidos para o ambiente de homologacao disponivel em https://front.serverest.dev/login.

# ✅ Padrão de Qualidade:

- Estrutura limpa
- Scripts diretos
- Padronização Cypress
- Boa documentação

  

📄 Licenca

Este projeto e licenciado sob a licenca MIT.

Projeto desenvolvido por Anderson Felipe 🚀

