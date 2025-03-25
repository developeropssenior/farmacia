# Sistema de Controle do Instituto Vittai

Sistema web para gerenciamento de estoque de medicamentos do Instituto Vittai.

## Funcionalidades

- Autenticação e controle de acesso
- Cadastro de medicamentos
- Controle de entrada e saída
- Histórico de movimentações
- Notificações de baixo estoque
- Relatórios
- Interface responsiva
- Suporte a múltiplas filiais

## Tecnologias Utilizadas

- Frontend: React.js
- Backend: Node.js com Express
- Banco de Dados: PostgreSQL
- ORM: Prisma
- Autenticação: JWT

## Requisitos

- Node.js 18+
- PostgreSQL 14+
- npm ou yarn

## Configuração do Projeto

1. Clone o repositório
2. Instale as dependências:
   ```bash
   # Backend
   cd backend
   npm install

   # Frontend
   cd frontend
   npm install
   ```

3. Configure as variáveis de ambiente:
   - Copie o arquivo `.env.example` para `.env` no diretório backend
   - Ajuste as configurações conforme necessário

4. Execute as migrações do banco de dados:
   ```bash
   cd backend
   npx prisma migrate dev
   ```

5. Inicie os servidores:
   ```bash
   # Backend
   cd backend
   npm run dev

   # Frontend
   cd frontend
   npm start
   ```

## Estrutura do Projeto

```
farmacia/
├── backend/           # API Node.js
├── frontend/         # Aplicação React
└── README.md
```

## Licença

MIT 