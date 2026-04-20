<h1 align="center">Gabriel Alencar</h1>

<p align="center">
  <strong>Desenvolvedor Full Stack & Mobile</strong><br/>
  TypeScript · Node.js · Flutter · Python · PostgreSQL · Docker
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gabriel-alencar-a04a12267/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:gabrielalencardearaujo04@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## Sobre mim

Desenvolvedor com experiência em **backend**, **mobile** e **automação**, especializado em construir produtos reais — do zero ao deploy em produção. Tenho background em infraestrutura de TI, o que me dá uma visão completa da stack: do código ao servidor.

Atualmente cursando **Análise e Desenvolvimento de Sistemas** no UniCEUB, com foco em arquitetura de software, sistemas distribuídos e desenvolvimento mobile multiplataforma.

- Construo APIs robustas com **NestJS** e **Node.js/Express**, seguindo Clean Architecture
- Desenvolvo apps mobile com **Flutter** para iOS e Android
- Faço deploy de aplicações containerizadas com **Docker** em VPS Linux, com CI/CD via GitHub Actions
- Trabalho com object storage (**MinIO**), cache (**Redis**), filas e comunicação em tempo real
- Integro serviços externos: pagamento PIX, WhatsApp API, Firebase Auth e provedores de dados

---

## Stack

### Linguagens
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="36" title="TypeScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="36" title="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="36" title="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="36" title="Dart"/>
</p>

### Backend & APIs
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="36" title="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="36" title="NestJS"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="36" title="Express"/>
</p>

### Mobile & Frontend
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="36" title="Flutter"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="36" title="React"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="36" title="Vue.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="36" title="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="36" title="CSS3"/>
</p>

### Banco de Dados & Storage
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="36" title="PostgreSQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="36" title="MySQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="36" title="Redis"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="36" title="SQLite"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" height="36" title="Prisma ORM"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/minio/minio-original.svg" height="36" title="MinIO"/>
</p>

### DevOps & Infra
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="36" title="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="36" title="Linux"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="36" title="Git"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="36" title="GitHub Actions"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="36" title="Firebase"/>
</p>

---

## Projetos em Destaque

### [Mão Na Roda](https://github.com/alencarrgabriel/mao-na-roda-bot-ts) — Chatbot de Consulta Veicular
> Bot WhatsApp de consulta veicular com sistema de pagamento PIX integrado, **em operação real gerando receita**.

- Funil completo: consulta gratuita → upsell → PIX → entrega automática de PDF
- Integração com Z-API (WhatsApp), OpenPix (PIX) e APIs de dados veiculares
- Sistema de sessões com expiração por inatividade, debounce de webhooks duplicados e fila de retry automático
- Painel admin com métricas de funil, receita e logs em tempo real
- Deploy em VPS Linux com Docker Compose, Caddy (HTTPS automático) e monitoramento via Sentry

**Stack:** `TypeScript` `Node.js` `Express` `Prisma` `PostgreSQL` `Redis` `Docker` `Caddy`

---

### [InteraEdu](https://github.com/alencarrgabriel/intera_edu) — Rede Social Acadêmica
> Rede social exclusiva para universitários com verificação de identidade via e-mail institucional.

- Backend NestJS 10 com TypeORM, autenticação JWT e arquitetura modular
- App Flutter 3 com Clean Architecture, BLoC e endpoints multiplataforma (Android/Web/iOS)
- Object storage com **MinIO** para upload de arquivos e mídia
- Infraestrutura containerizada com Docker Compose (Node.js 20, PostgreSQL 16, Redis 7, MinIO)
- Documentação técnica completa: arquitetura, padrões e status de MVP em `/docs`

**Stack:** `Flutter` `Dart` `NestJS` `TypeScript` `TypeORM` `PostgreSQL` `Redis` `MinIO` `Docker`

---

### [Feliz no Simples](https://github.com/alencarrgabriel) — Plataforma Mobile + Backend
> Aplicação completa com app mobile e API REST seguindo Clean Architecture.

- App Flutter multiplataforma com gerenciamento de estado via BLoC e injeção de dependência com GetIt
- Backend NestJS com autenticação JWT e login social (Google/Apple via Firebase Auth)
- Dados geoespaciais com PostgreSQL + PostGIS
- Chat em tempo real com Socket.IO e cache com Redis
- Pipeline CI/CD automatizado com GitHub Actions + Docker

**Stack:** `Flutter` `Dart` `NestJS` `TypeScript` `PostgreSQL` `PostGIS` `Redis` `Socket.IO` `Firebase` `Docker`

---

### [Gerador de Recibos](https://github.com/alencarrgabriel/GeradorRecibos) — App Desktop Offline
> Aplicação desktop para geração de recibos PDF, controle de caixa e gestão financeira operacional.

- Interface desktop com PySide6 (Qt 6), temas claro/escuro e suporte a rede local
- Geração de PDF com ReportLab e backup automático
- Autenticação com PBKDF2 e Clean Architecture

**Stack:** `Python` `PySide6` `ReportLab` `SQLite`

---

### [Dashboard de Vendas](https://github.com/alencarrgabriel/DashboardVendas) — Análise de Dados
> Dashboard interativo para análise de vendas por filial, produto, cidade e forma de pagamento.

**Stack:** `Python` `Pandas` `Plotly Express` `Streamlit`

---

## GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=alencarrgabriel&show_icons=true&theme=dark&hide_border=true&count_private=true"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alencarrgabriel&layout=compact&theme=dark&hide_border=true"/>
</p>

---

<p align="center">
  <strong>Aberto a oportunidades</strong> — back-end, mobile ou full stack.<br/>
  <a href="mailto:gabrielalencardearaujo04@gmail.com">gabrielalencardearaujo04@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/gabriel-alencar-a04a12267/">LinkedIn</a>
</p>
