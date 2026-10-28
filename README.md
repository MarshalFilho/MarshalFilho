# Marshal Borges

Estudante de Engenharia de Software (Estácio, formatura prevista em jan/2028) e desenvolvedor full-stack de Goiânia. Construo produtos do banco de dados à tela, com Laravel, Python, Kotlin e Vue/Nuxt, e uso IA para ir da ideia ao produto no ar, cuidando de custo, privacidade dos dados e confiabilidade da resposta do modelo.

## O que eu construo

**[Fiquei no Azul](https://fiqueinoazul.com.br)** — app de controle financeiro pessoal, feito do zero e lançado por mim. Uma frase como "50 mercado ontem nubank 3x" vira um lançamento categorizado, a IA lê a fatura do cartão em PDF de qualquer banco e um bot de WhatsApp registra gastos por mensagem. Kotlin, Spring Boot, Vue 3 e PostgreSQL.

**HS Desk (trabalho)** — na Hardsystem Informática, trabalho no HS Desk, uma plataforma de helpdesk multi-tenant, do back-end ao front-end:
- **API (Laravel 11, DDD):** schemas de banco isolados por cliente, trilha de auditoria imutável com triggers do PostgreSQL, cobrança recorrente com Stripe e filas com Redis e Horizon.
- **Front-end (Nuxt 3, Vue 3, TypeScript, Pinia):** quadro Kanban, editor de texto rico, painéis de SLA em tempo real e mais de 400 testes unitários e Cypress.
- **Serviço de IA (FastAPI, LangChain, LangGraph):** resumo executivo de reuniões a partir de áudio, triagem de tickets, análise de sentimento, tradução de Pull Requests em notas para clientes e um chatbot de suporte com RAG.

**[Biscuit Scraper](https://github.com/MarshalFilho/biscuit_scraper)** — pipeline de inteligência de mercado: coleta preços e anúncios de marketplaces, organiza os dados e gera diagnósticos com o Gemini em um painel Nuxt 3.

Os dois primeiros têm código privado.

## Como eu trabalho com IA

- Uso IA onde ela ajuda de verdade e regras simples onde ela erraria: no Fique no Azul, o lançamento rápido é por regras (instantâneo, grátis e testável), e a IA fica para ler faturas e escrever relatórios.
- Penso no custo desde o início: cota de uso por conta, modelo mais barato que dá conta e roteamento de usuários do plano gratuito para modelos gratuitos.
- Trato a saída do modelo como dado não confiável: esquemas JSON estruturados, validação e nova tentativa, mascaramento de dados pessoais e defesa contra prompt injection.
- Uso o Claude Code no dia a dia para construir e iterar rápido.

## Stack

**Back-end:** PHP (Laravel), Python (FastAPI), Kotlin (Spring Boot), PostgreSQL, Redis  
**Front-end:** Vue 3, Nuxt 3, TypeScript, Pinia  
**IA:** Claude Code, LangChain, LangGraph, RAG, APIs Gemini, OpenAI e DeepSeek, Whisper, saídas estruturadas  
**Dados e automação:** Playwright, Supabase  
**Testes e infra:** Cypress, JUnit, Vitest, Docker, GitHub Actions, Google Cloud Run

## Contato

marshalfilho@gmail.com · [fiqueinoazul.com.br](https://fiqueinoazul.com.br)
