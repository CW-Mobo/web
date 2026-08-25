# Web

> Interface web do Projeto Mobo para monitoramento, gerenciamento e visualização dos dados do sistema de colheita automatizada de lichia.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)

---

## 📋 Sobre

O **Mobo Web** é a aplicação web do Projeto Mobo, responsável pela interface de gerenciamento e monitoramento do sistema.

A aplicação permite visualizar informações coletadas pelo sistema, acompanhar dados da colheita, gerenciar usuários e acessar os recursos disponibilizados pela API do Mobo.

---

## ✨ Funcionalidades

- 🔐 Autenticação e gerenciamento de sessão
- 👤 Gerenciamento de usuários
- 📊 Dashboard com gráficos e indicadores
- 🌱 Visualização de dados relacionados à produção
- 🤖 Monitoramento do braço mecânico
- 📡 Visualização de dados IoT
- 🗺️ Visualização de sensores e dispositivos
- 📈 Visualização de histórico de dados
- 🖼️ Gerenciamento e visualização de imagens

---

## 🛠️ Tecnologias

- **Next.js** — framework da aplicação
- **React** — construção da interface
- **TypeScript** — tipagem estática
- **Axios** — comunicação com a API
- **React Chart.js** — gráficos e visualização de dados
- **Leaflet** — mapas e localização de dispositivos
- **Lucide React** — ícones
- **ESLint** — análise de código
- **Prettier** — formatação de código
- **Vitest** — testes

---

## 🏗️ Arquitetura

```text
web/
├── public/
├── src/
│   ├── app/
|   ├── components/
|   ├── hooks/
|   ├── services/
|   ├── styles/
|   └── types/
├── .env.example
├── .gitignore
├── eslint.config.mjs
├── LICENSE
├── next.config.ts
├── package.json
├── package-lock.json
├── README.md
└── tsconfig.json
```

---

## 🚀 Como Rodar Localmente

### 1. Clonar o Repositório

```bash
git clone https://github.com/CW-Mobo/web.git
cd web
```

### 2. Instalar Dependências

```bash
npm install
```

#### Configurar variáveis de ambiente

Na pasta `web`, crie um arquivo `.env.local` baseado no `.env.example` disponível no repositório.

> Não precisa mudar nada, para o local o exemplo do .env.example já serve.

### 3. Executar o Web

```bash
npm run dev
```

> ⚠️ A API precisa estar em execução para que todas as funcionalidades do Web funcionem corretamente.

Acesse [http://localhost:3000](http://localhost:3000) no navegador.

> 💡 O web está configurado para consumir a API em `http://localhost:5000`. Caso altere a porta da API, ajuste também a URL da API no arquivo de conexão do web.

---

## 🌐 Deploy

A aplicação Web está hospedada na Vercel.

**Produção:** https://mobocw.vercel.app/

---

## 📄 Licença

Este projeto está sob a licença MIT.

Consulte o arquivo LICENSE para mais informações.
