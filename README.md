<div align="center">

<h1>Raphael Sinelli</h1>
<h3>Software &amp; Data Engineer in training</h3>

<a href="https://github.com/Raphael-Sinelli">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=620&lines=Estudante+de+ADS+%40+FIAP;Full-Stack+Developer+%7C+Java+%2F+React;Dados+%7C+Python+%2B+SQL+%2B+ETL;Construindo+projetos+reais+em+produ%C3%A7%C3%A3o" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/FIAP-ADS%202027-000000?style=flat-square&labelColor=1a1a2e"/>
<img src="https://img.shields.io/badge/Localização-Ribeirão%20Pires%2C%20SP-334155?style=flat-square&labelColor=1a1a2e"/>

<br/><br/>

<a href="https://linkedin.com/in/raphael-sinelli"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:raphaelsinelli@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Raphael-Sinelli"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

### Sobre mim

Estudante de **Análise e Desenvolvimento de Sistemas** na FIAP, com atuação prática tanto em **desenvolvimento full-stack** (Java/Quarkus, Spring Boot, React/TypeScript) quanto em **dados** (Python, pandas, SQL analítico, ETL, estatística aplicada).

Construí um portfólio com **seis projetos reais em produção**, incluindo uma plataforma full-stack com autenticação JWT, um analisador de repositórios com OAuth2 e infraestrutura em Terraform/AWS, e um pipeline de dados vivo que ingere indicadores econômicos do Banco Central diariamente.

No dia a dia, também sou responsável pelo desenvolvimento e manutenção do site institucional da empresa onde trabalho, além da gestão de campanhas de Meta Ads e automação do catálogo digital.

```txt
🎯 Open to: Vaga em Desenvolvimento (Front-end, Back-end ou Full-Stack), Dados ou DevOps
🗣️ Idiomas: Português (nativo) · Inglês (avançado) · Alemão (básico)
```

---

### Projetos em Destaque

<details open>
<summary><b>📊 Econ Data Pipeline</b></summary>
<br/>

Pipeline de dados vivo que ingere indicadores econômicos (SELIC, IPCA, câmbio) da API do Banco Central diariamente via GitHub Actions, com tratamento e validação em pandas — incluindo anualização da taxa SELIC via juros compostos — persistência em PostgreSQL e dashboard de visualização de séries históricas em produção.

| | |
|---|---|
| **Stack** | Python · pandas · PostgreSQL (Neon) · Next.js |
| **Automação** | GitHub Actions (ingestão diária agendada) |
| **Deploy** | [econ-data-pipeline-three.vercel.app](https://econ-data-pipeline-three.vercel.app) |

</details>

<details>
<summary><b>🏋️ LiftCurve</b></summary>
<br/>

Aplicação full stack para gerenciamento de treinos, com autenticação JWT e refresh token, testes automatizados e CI/CD completo.

| | |
|---|---|
| **Stack** | Java 21 (Quarkus) · React 19 · TypeScript · PostgreSQL · Docker |
| **Testes** | JUnit 5, Testcontainers, Vitest |
| **CI/CD** | GitHub Actions |
| **Deploy** | [liftcurve.vercel.app](https://liftcurve.vercel.app/login) |

</details>

<details>
<summary><b>🔍 RepoMind</b></summary>
<br/>

Analisador de repositórios GitHub com tool use real de IA — o modelo decide quais ferramentas chamar (commits, README, issues) num loop de agente, não um prompt único. OAuth2 real com GitHub, cache por commit SHA e infraestrutura versionada em Terraform.

| | |
|---|---|
| **Stack** | Java 21 (Spring Boot) · Spring Security OAuth2 · React 19 · TypeScript · PostgreSQL · Redis |
| **Infra** | AWS (VPC, RDS, ECS Fargate) via Terraform |
| **Deploy** | [repomind-flame.vercel.app](https://repomind-flame.vercel.app) |

</details>

<details>
<summary><b>✅ QA Portfolio</b></summary>
<br/>

Suíte independente de testes de API e E2E contra sistemas reais em produção (LiftCurve e RepoMind), com CI automatizado e estratégia de teste documentada.

| | |
|---|---|
| **Stack** | Playwright · RestAssured · TypeScript · Java |
| **Repositório** | [github.com/Raphael-Sinelli/qa-portfolio](https://github.com/Raphael-Sinelli/qa-portfolio) |

</details>

<details>
<summary><b>🛋️ Site Casa Sinelli</b></summary>
<br/>

Site institucional em produção com catálogo de mais de 120 produtos, foco em SEO, performance e responsividade — utilizado diariamente pela empresa.

| | |
|---|---|
| **Stack** | Next.js · TypeScript · Tailwind CSS · GSAP |
| **Deploy** | [casasinelli.com.br](https://casasinelli.com.br) |

</details>

---

### Foco em Dados

| Domínio | Ferramentas | Aplicação |
|---|---|---|
| Ingestão de dados | Python, API Banco Central | Pipeline diário automatizado via GitHub Actions |
| Tratamento de dados | pandas | Anualização de taxas via juros compostos, validação e limpeza |
| Persistência | PostgreSQL (Neon) | Modelagem relacional (DER/MER) de séries históricas |
| Análise estatística | SciPy / testes de hipótese | Correlação de Spearman, testes de Kruskal-Wallis, detecção de outliers |
| Visualização | Next.js, Power BI (noções) | Dashboards de séries históricas e métricas de negócio |

---

### Stack Técnica

<div align="center">

**Linguagens**
<br/>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>

**Front-end**
<br/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white"/>
<img src="https://img.shields.io/badge/React%20Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>
<img src="https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white"/>

**Back-end**
<br/>
<img src="https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/REST%20APIs-005571?style=flat-square"/>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger%2FOpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>

**Banco de Dados**
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Oracle%20SQL-F80000?style=flat-square&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/DER%2FMER-4169E1?style=flat-square"/>

**Dados & Análise**
<br/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/ETL-4169E1?style=flat-square"/>
<img src="https://img.shields.io/badge/Estatística%20Aplicada-4169E1?style=flat-square"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>

**Testes & Qualidade**
<br/>
<img src="https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white"/>
<img src="https://img.shields.io/badge/Testcontainers-1D63ED?style=flat-square&logo=testcontainers&logoColor=white"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
<img src="https://img.shields.io/badge/RestAssured-25A162?style=flat-square"/>

**Cloud, DevOps & Ferramentas**
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white"/>

</div>

---

### Experiência Profissional

**Desenvolvedor Web · Administrativo · Atendimento**
`Dez/2025 — Atual`

Desenvolvimento e manutenção do site institucional, implementação de melhorias na plataforma e gerenciamento de campanhas Meta Ads. Também atuo no atendimento ao cliente, organização do catálogo digital (automatizado em Python) e apoio às atividades administrativas.

`Next.js` `TypeScript` `Meta Ads` `Python` `Atendimento ao cliente`

<br/>

**Operador de Teleatendimento — PersonalCob**
`Jan/2025 — Dez/2025`

Atendimento de alto volume de clientes, negociação de demandas, resolução de problemas e cumprimento de metas operacionais.

`Comunicação` `Organização` `Trabalho sob pressão`

---

### Certificações

<div align="center">

<img src="https://img.shields.io/badge/HackerRank-Software%20Engineer-2EC866?style=flat-square&logo=hackerrank&logoColor=white"/>
<img src="https://img.shields.io/badge/HackerRank-Frontend%20Developer%20(React)-2EC866?style=flat-square&logo=hackerrank&logoColor=white"/>
<img src="https://img.shields.io/badge/HackerRank-SQL-2EC866?style=flat-square&logo=hackerrank&logoColor=white"/>

</div>

---

### Formação

| Instituição | Curso | Status |
|---|---|---|
| FIAP | Análise e Desenvolvimento de Sistemas | Conclusão prevista Jul/2027 |
| ETEC Ribeirão Pires "Maria Cristina Medeiros" | Técnico em Química | Concluído Jul/2024 |
| Colégio Clarassoti | Ensino Médio | Concluído 2024 |

---

### GitHub Analytics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Raphael-Sinelli&theme=tokyonight&hide_border=true&background=0d1117&ring=38BDF8&fire=F59E0B&currStreakLabel=38BDF8&cache_seconds=86400"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Raphael-Sinelli&theme=react-dark&hide_border=true&bg_color=0d1117&color=38BDF8&line=38BDF8&point=ffffff&cache_seconds=86400"/>

</div>

---

### Foco Atual

```yaml
Aprendendo: Estatística aplicada avançada, arquitetura de dados, AWS
Construindo: Novos projetos de portfólio (dev + dados)
Explorando: Oportunidades de vaga em desenvolvimento (front-end, back-end ou full-stack), dados e DevOps
Aberto a: Vaga presencial, híbrida ou remota
```

---

### Conecte-se

<div align="center">

<a href="mailto:raphaelsinelli@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/raphael-sinelli"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Raphael-Sinelli"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

<div align="center">

*"Código bem testado é a diferença entre achar que funciona e saber que funciona."*

</div>
