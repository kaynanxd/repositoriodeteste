
# 🎮 LetterPlay

![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react&style=flat-square)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)

**LetterPlay** é uma plataforma web desenvolvida para entusiastas de videogames, inspirada no conceito do Letterboxd. O sistema permite descobrir jogos, criar listas personalizadas ("Watchlists"), avaliar títulos com notas e reviews, e acompanhar o progresso de jogatina (Jogado, Dropado, Não Iniciado).

O projeto utiliza a API do **IGDB** para fornecer uma base de dados robusta, combinando dados externos com um sistema interno de avaliações da comunidade.

---

## 📸 Screenshots

*(Coloque aqui uma imagem da tela inicial)*
*(Coloque aqui uma imagem da tela de detalhes do jogo)*

---

## 🚀 Funcionalidades

### 🌟 Principais
- **Busca Híbrida Inteligente:** Pesquise jogos na API do IGDB e veja instantaneamente se eles já possuem nota na comunidade local.
- **Sistema de Avaliação:** Dê notas (1 a 5 estrelas) e escreva reviews detalhados.
- **Média da Comunidade:** Cálculo automático da nota média baseada nas reviews dos usuários, com atualização em tempo real na interface.
- **Ranking Semanal:** Exibição dos jogos mais bem avaliados pela comunidade.

### 📂 Gerenciamento
- **Minhas Listas:** Crie listas temáticas (ex: "RPGs para zerar", "Favoritos").
- **Biblioteca Pessoal:** Gerencie o status de cada jogo (`JOGADO`, `AINDA NAO JOGADO`, `DROPADO`).
- **Favoritos:** Adicione jogos rapidamente à lista de favoritos com um clique.

### 🛠️ Diferenciais Técnicos
- **Persistência Otimizada:** As médias de notas são calculadas e persistidas no banco de dados para evitar lentidão em consultas pesadas.
- **Normalização de Dados:** O Frontend adapta automaticamente dados vindos de fontes externas (IGDB) e internas (PostgreSQL) para uma experiência de usuário fluida.

---

## 💻 Tecnologias Utilizadas

### Backend
- **Linguagem:** Python 3.10+
- **Framework:** FastAPI (Async)
- **ORM:** SQLAlchemy 2.0 (Async)
- **Banco de Dados:** PostgreSQL
- **Validação:** Pydantic

### Frontend
- **Framework:** React 18
- **Estilização:** TailwindCSS 3.0
- **Build Tool:** Vite
- **HTTP Client:** Axios
- **Roteamento:** React Router DOM

---

## ⚙️ Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
- [Python 3.10+](https://www.python.org/)
- [Node.js 18+](https://nodejs.org/)
- [PostgreSQL](https://www.postgresql.org/)
- Credenciais de API do [IGDB (Twitch Developer)](https://dev.twitch.tv/)

---

## 🔧 Instalação e Configuração

### 1. Clonar o Repositório

```bash
git clone [https://github.com/seu-usuario/letterplay.git](https://github.com/seu-usuario/letterplay.git)
cd letterplay
