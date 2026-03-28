# Drip Store - Frontend
Interface moderna e responsiva desenvolvida para a plataforma de e-commerce Drip Store, focada na experiência do usuário e performance.

[Visão Geral](#-visão-geral) | [Tecnologias](#-tecnologias-utilizadas) | [Acesso](#-deploy--acesso-rápido) | [Setup](#-como-executar) | [Estrutura](#-organização-do-projeto)

## Visão Geral
Este projeto representa a camada visual da loja virtual. A aplicação consome uma API REST para renderizar o catálogo de produtos e gerenciar as interações do carrinho, garantindo uma navegação fluida e intuitiva.

##  Tecnologias Utilizadas
*   **Framework:** React (Vite)
*   **Estilização:** Tailwind CSS
*   **Linguagem:** JavaScript (ES6+)
*   **Deploy:** Vercel

## Deploy & Acesso Rápido
A aplicação está publicada e pronta para testes no link abaixo:
➡️ Drip Store Digital - Vercel: https://drip-store-seven-flax.vercel.app/

---

##  Como Executar

### 1. Obtenção do Código
Clone o repositório:
```
git clone https://github.com/fefter/drip-store-frontend.git
```

Acesse a pasta 
```
cd drip-store-frontend
```

Instale as dependências
```
npm install
```

Inicialização
```
npm run dev
```

## Arquitetura do projeto
```
src/
├── components/ # Componentes reutilizáveis (Botões, Cards, etc.)
├── pages/      # Telas principais da aplicação
├── services/   # Integração com a API Backend
├── assets/     # Arquivos estáticos (Imagens, ícones)
└── main.jsx    # Ponto de entrada do React
```

## Autora
---
Projeto desenvolvido por Fernanda Pinheiro.
