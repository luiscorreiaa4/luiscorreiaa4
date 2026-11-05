<div align="center">
  <a href="https://www.linkedin.com/in/luis-correia-de-araujo/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:pleluis47@gmail.com">
    <img src="https://img.shields.io/badge/-Email-%23D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://drive.google.com/file/d/1PoFAAekN8icBVJLF7aPp769s-5q-8qhd/view?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/-Currículo-black?style=for-the-badge&logo=google-docs&logoColor=white" alt="Currículo" />
  </a>
</div>

---

### Olá! Eu sou o Luís Correia 👋

**Desenvolvedor Full Stack** em Maceió, AL, graduando em **Sistemas de Informação no CESMAC** (previsão dez/2028) e formado em **Desenvolvimento Web pela Trybe** (1.500h).

Construo aplicações web de ponta a ponta com **TypeScript, React, Node.js, Express e PostgreSQL**: do esquema SQL e das migrações até testes automatizados, CI e deploy. Meu projeto principal, o **CalorieSync**, está em produção e pode ser testado sem cadastro.

* 🎓 **Formação:** Bacharelado em Sistemas de Informação no CESMAC (cursando 4º período) e Desenvolvimento Web Full Stack na Trybe.
* 🔬 **Estudos complementares:** Fundamentos de Ciência da Computação, estruturas de dados e algoritmos com o *CS50's Introduction to Computer Science* (HarvardX).
* 🛠️ **Vivência em TI:** Quase 2 anos em Suporte Técnico na VTech/Sistematech Informática, com diagnóstico de causa-raiz, resolução de incidentes e atendimento a usuários.
* 📍 **Disponibilidade:** Maceió, AL (presencial, híbrido ou remoto), para estágio ou vaga júnior.

---

### 🚀 Projetos em Destaque

#### 🍏 [CalorieSync — Contador de calorias full stack](https://github.com/luiscorreiaa4/contador-de-calorias)
**[▶ Abrir a demo](https://caloriesync-luiscorreia.netlify.app/)** · o botão *Ver demonstração* cria uma conta de visitante que dura 2 horas.

`React 19` • `TypeScript` • `Node.js` • `Express` • `PostgreSQL` • `TanStack Query` • `Zod` • `Vitest` • `Playwright` • `Docker` • `GitHub Actions`

* Calcula TMB, TDEE e metas de macros e registra refeições com a Tabela TACO, com histórico em gráficos (calorias, macros, peso e gordura corporal), PWA, navegação por swipe no mobile e tema claro/escuro.
* API Express em 4 camadas (`routes → controllers → services → models`) com **SQL parametrizado sem ORM**, transações atômicas, validação Zod compartilhada com o frontend e **19 migrações versionadas** com teste de rollback.
* **Segurança como requisito:** confirmação de e-mail com códigos em HMAC-SHA256, JWT em cookie com revogação, **MFA por TOTP**, painel admin com **RBAC e trilha de auditoria**, rate limiting, e exportação e exclusão de conta (LGPD).
* **CI completo:** typecheck, ESLint, Gitleaks, detecção de código morto, testes de backend em PostgreSQL real, testes de frontend com Vitest + Testing Library, **E2E com Playwright**, smoke de carga e build Docker.
* Deploy em Netlify, Render e Neon. Decisões de arquitetura documentadas como ADRs.

#### 🏆 [TFC — API de Gerenciamento de Campeonatos](https://github.com/luiscorreiaa4/TFC) · *projeto Trybe*
`Node.js` • `TypeScript` • `Express` • `MySQL` • `JWT`
* API REST para partidas e classificação de torneios, com rotas autenticadas via JWT e cálculo dinâmico da tabela de pontuação.

#### 💼 [Nexus Consultoria — Plataforma de Gestão de Chamados](https://github.com/luiscorreiaa4/Projeto3oPeriodo) · *projeto acadêmico*
`Node.js` • `Express` • `EJS` • `PostgreSQL`
* Plataforma web com autenticação de usuários, gestão de chamados e serviços e persistência em PostgreSQL.

---

### 🛠️ Tecnologias e Ferramentas

**Front-end**
<p align="left">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white" />
  <img alt="React Router" src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**Back-end e Banco de Dados**
<p align="left">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="Zod" src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />
  <img alt="JWT" src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" />
</p>

**Testes, DevOps e Deploy**
<p align="left">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Netlify" src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" />
  <img alt="Render" src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" />
</p>

---

### 📊 Estatísticas do GitHub

<div align="center">
  <picture>
    <source
      srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=luiscorreiaa4&theme=dracula"
      media="(prefers-color-scheme: dark)"
    />
    <img src="https://github-readme-stats.vercel.app/api?username=luiscorreiaa4&hide=stars&show_icons=true&theme=dracula" alt="GitHub Stats" />
  </picture>
</div>
