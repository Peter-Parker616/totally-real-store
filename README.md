Instalação
docker-compose up

# 🛍️ Favorite Products Platform

Plataforma desenvolvida para gerenciamento de clientes e produtos favoritos utilizando API externa.

O projeto consome dados da Fake Store API e permite que usuários salvem produtos favoritos para futuras compras.

---

# 🚀 Tecnologias Utilizadas

## Frontend
- React
- Vite
- TailwindCSS
- Axios

## Backend
- Node.js
- Express
- Prisma ORM
- SQLite

## DevOps & Infra
- Docker
- Docker Compose
- GitHub Actions
- Cloudflare Pages
- Railway/Render

---

# 🌐 API Externa

Utilizada:
- :contentReference[oaicite:0]{index=0}

---

# 📦 Funcionalidades

## 👤 Clientes
- Criar cliente
- Listar clientes
- Editar cliente
- Remover cliente

## ❤️ Favoritos
- Adicionar favoritos
- Listar favoritos
- Remover favoritos

---

# ⚙️ Regras de Negócio

- O e-mail do cliente não pode ser duplicado
- Produtos favoritos não podem ser duplicados para o mesmo cliente
- O produto precisa existir na Fake Store API

---

# 🐳 Executando com Docker

## Pré-requisitos

- Docker
- Docker Compose

---

## Clone o repositório

```bash
git clone https://github.com/seuusuario/seurepositorio.git
```

## Acesse a pasta

```bash
cd favorite-products
```

## Execute o projeto

```bash
docker-compose up --build
```

---

# 🔥 Executando Localmente

## Backend

```bash
cd backend
npm install
npm run dev
```

## Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# 📁 Estrutura do Projeto

```txt
favorite-products/
│
├── backend/
├── frontend/
├── docker-compose.yml
└── .github/workflows/
```

---

# 🔄 CI/CD

O projeto possui pipeline automatizada utilizando GitHub Actions para:

- Build da aplicação
- Validação automática
- Deploy automatizado

---

# ☁️ Deploy

## Frontend
Cloudflare Pages

## Backend
Railway/Render

---

# 📊 Monitoramento

Monitoramento e Analytics realizados utilizando serviços da Cloudflare.

---

# 📸 Demonstração

## Aplicação
- Frontend: https://seu-front.pages.dev
- Backend: https://sua-api.up.railway.app

---

# 👨‍💻 Desenvolvido por:
João Arthur Costa Oliveira
37023623

---

# 📄 Licença

Projeto acadêmico desenvolvido para fins educacionais.
