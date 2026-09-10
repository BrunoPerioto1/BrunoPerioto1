## Bruno Zubiolo Perioto

Desenvolvedor Full-Stack com foco em backend. Hoje trabalho na **GBM Tech by nstech**, numa plataforma SaaS
de gestão logística e portuária — quatro módulos (hidroviário, marítimo, rodoviário e ferroviário), arquitetura
multi-tenant e integrações com serviços legados que não podem cair.

Gosto do trabalho que acontece antes do código bonito: modelar o banco direito, decidir o que é regra de
negócio e o que é detalhe de entrega, e escrever teste para a parte que realmente quebra.

📍 Santos-SP · 📫 [brunzp1934@gmail.com](mailto:brunzp1934@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/bruno-perioto/)

---

### O que estou construindo

**SportsBet Manager** — um controle de apostas esportivas que nasceu de um problema meu: eu desistia da
planilha em duas semanas porque digitar era chato demais. Então o sistema aceita um **print do bilhete**, um
**áudio** ou uma **mensagem de tipster**, e transforma qualquer um dos três em aposta estruturada.

[![Dashboard do SportsBet Manager](https://raw.githubusercontent.com/BrunoPerioto1/sts/main/docs/screenshots/02-dashboard.png)](https://github.com/BrunoPerioto1/sts)

| Repositório | O que tem de interessante |
|---|---|
| **[stsbackend](https://github.com/BrunoPerioto1/stsbackend)** · NestJS | Ingestão multimodal com visão e transcrição, uma camada de normalização determinística por cima da saída do LLM, e casamento com tips pendentes feito por score local — sem IA nenhuma. |
| **[sts](https://github.com/BrunoPerioto1/sts)** · React | O print vira formulário preenchido, com a origem de cada campo marcada. Compressão da imagem no browser, e layout mobile de verdade. |

A parte que mais me ensinou foi aceitar que **Structured Outputs garante o formato do JSON, não a sanidade
dele**. Todo campo que vem de um modelo passa por normalização testada antes de encostar no domínio.

---

### Stack

**Back-end** — Node.js, NestJS, Golang, APIs REST, Clean Architecture, CQRS, JWT (RS256), RBAC
**Front-end** — React, TypeScript, Vite, Module Federation, TanStack Router/Query, Zustand, Tailwind
**Dados** — PostgreSQL, Kysely (queries type-safe), Prisma, Kanel
**Infra e qualidade** — AWS (EC2, PM2), Docker, Azure DevOps, Jest, Prometheus, Sentry

Também mexo com Python para OCR e automação, e já construí agentes com LangChain.

---

### Formação

Análise e Desenvolvimento de Sistemas — **Fatec Baixada Santista** (2024–2026)
Inglês avançado
