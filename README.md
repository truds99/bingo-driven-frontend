# 🎯 Bingo Driven - Front-End

Interface web para o projeto **Bingo Driven**, desenvolvido com Vite + React e conectado ao back-end via API. Totalmente preparado para deploy automatizado via **Vercel**.

---

## 🌐 Link do Projeto

🔗 https://bingo-driven-frontend-gamma.vercel.app/

---

## 🚀 Tecnologias Utilizadas

- Vite
- React
- TypeScript
- TailwindCSS
- Axios
- Vercel (CD)
- GitHub Actions

---

## 📦 Rodando localmente com Docker

### ✅ Pré-requisitos
- Docker instalado

### 🔧 Comandos
```bash
docker build -t bingo-frontend .
docker run -p 5173:5173 --env-file .env bingo-frontend
```

---

## 🐳 Como rodar o projeto com Docker Compose

1. Clone o repositório do front-end:

```bash
git clone https://github.com/seu-usuario/bingo-driven-frontend.git
cd bingo-driven-frontend
```

2. Crie um arquivo .env na raiz com a URL do back-end:

```bash
VITE_BACKEND=http://localhost:5000
```

3. Rode o Docker Compose:

```bash
docker-compose up --build
```

A aplicação estará disponível em: http://localhost:8080

---

## 📦 Rodando localmente com Vite

### ✅ Requisitos
- Node.js 20+

### 🔧 Comandos
```bash
npm install
npm run dev
```

---

## 🔐 Variáveis de ambiente

Crie um arquivo `.env` com a seguinte variável:

```
VITE_BACKEND=https://bingo-driven-backend-1.onrender.com
```

---

## 🔄 Deploy Automático

- O projeto está conectado à Vercel.
- Pushs no branch `main` disparam automaticamente o deploy.

---

## 📁 Estrutura

```
src/
├── components/
├── pages/
├── services/ (axios config)
├── App.tsx
└── main.tsx
```

---

## ✨ Contribuição

Pull requests são bem-vindos. Para mudanças maiores, abra uma issue primeiro para discutirmos o que você gostaria de alterar.

---

## 🧼 Licença

MIT
