<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Full-stack Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadofullstack?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadofullstack?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadofullstack?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadofullstack?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete Full-stack guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
A **full-stack** developer is someone who moves across both ends of a web application: the **front-end** (what runs in the browser — HTML, CSS, JavaScript and frameworks like React) and the **back-end** (what runs on the server — APIs, databases, authentication, deployment). It does not mean knowing everything at the same depth: it means being able to **deliver a whole feature**, from the screen to the database, and to talk fluently with specialists on each side. It is the most requested profile in startups, small companies and lean teams — and, in Brazil, one of the most common entry doors into programming.

This guide is for people starting from zero or who already know one side and want to close the loop. It organizes **roadmap, entry path, courses, documentation, tools, projects, certifications, salaries and communities**, prioritizing content that is **in Portuguese and free**. 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review. To go deeper on each side of the stack, also use the sibling guides on [Front-end](https://github.com/arthurspk/guiadofrontend), [Back-end](https://github.com/arthurspk/guiadobackend) and [TypeScript](https://github.com/arthurspk/guiadetypescript).

## 🗺️ Roadmap
- [roadmap.sh — Full Stack Developer](https://roadmap.sh/full-stack) — Community-made visual, interactive roadmap: HTML/CSS/JS, React, Node, databases, deployment — in the right order, with links per topic. 🆕 🇺🇸
- [roadmap.sh — Frontend](https://roadmap.sh/frontend) — The front-end half of the path, in detail: from semantic HTML to frameworks, testing and performance. 🆕 🇺🇸
- [roadmap.sh — Backend](https://roadmap.sh/backend) — The back-end half: APIs, authentication, relational and NoSQL databases, caching, queues and observability. 🆕 🇺🇸
- [roadmap.sh — JavaScript · SQL · Git e GitHub](https://roadmap.sh/javascript) — Sub-roadmaps of the fundamentals every full-stack developer needs; see also [SQL](https://roadmap.sh/sql), [Git and GitHub](https://roadmap.sh/git-github) and [API Design](https://roadmap.sh/api-design). 🆕 🇺🇸
- [developer-roadmap (GitHub)](https://github.com/nilbuild/developer-roadmap) — Source repository of the roadmaps above, one of the most starred on GitHub; good for following the yearly revisions. 🆕 🇺🇸
- [TechGuide — trilha Full-stack (Alura)](https://techguide.sh/pt-BR/path/full-stack/) — Brazilian career-path guide, with levels per technology and Portuguese content suggestions.
- [MDN — Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development) — Mozilla's official curriculum, revamped in 2025: fundamentals, HTML, CSS, JavaScript, accessibility, tooling and best practices. 🆕 🇺🇸
- [The Odin Project — Full Stack JavaScript path](https://www.theodinproject.com/paths/full-stack-javascript) — Free, project-based path from zero to full-stack with Node.js and React. 🇺🇸
- [Guia de Front-end · Guia de Back-end (Guia Dev Brasil)](https://github.com/arthurspk/guiadevbrasil) — Parent guide of the network with the sibling front-end and back-end guides: use them to go deeper on each side of the stack.

**Summary path** (follow in order; each step has resources in the sections below):

1. **How the web works** — browser, server, HTTP, DNS, what an API is. Without this, the rest becomes rote memorization.
2. **Basic front-end** — semantic HTML, CSS (flexbox, grid, responsiveness) and modern JavaScript (DOM, events, `fetch`, `async/await`).
3. **Tools of the trade** — terminal, Git and GitHub, VS Code, npm. Publish everything you build.
4. **Front-end with a framework** — React (or Vue), components, state, routing and API consumption. TypeScript comes in here.
5. **Back-end** — Node.js with Express/Fastify (or Python with Django/FastAPI, Java with Spring, PHP with Laravel): routes, REST, validation, authentication (JWT/sessions), environment variables.
6. **Databases** — SQL with PostgreSQL (modeling, JOIN, indexes), an ORM (Prisma/Drizzle) and NoSQL basics (MongoDB, Redis).
7. **Quality and delivery** — tests (Vitest/Jest, Playwright), Docker, CI with GitHub Actions and deployment (Vercel, Render, Railway, Fly.io).
8. **Real full-stack** — a framework that joins both ends (Next.js), security (OWASP Top 10), observability, caching and system design basics.

## 🚀 Where to start
1. **Understand the web before programming.** Read [How the Web works](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works) on MDN (Portuguese) and the [HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP) overview.
2. **Install the environment:** [Visual Studio Code](https://code.visualstudio.com/), [Git](https://git-scm.com/) and [Node.js](https://nodejs.org/en) (LTS version). On Windows, use [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install).
3. **HTML and CSS:** take the [Curso em Vídeo HTML5 and CSS3 course](https://www.youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n) or [freeCodeCamp's Responsive Web Design in Portuguese](https://www.freecodecamp.org/portuguese/learn/), and publish your first page on GitHub Pages with the [Git and GitHub course](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA).
4. **JavaScript:** [Curso em Vídeo's JavaScript course](https://www.youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1) and, to consolidate, [Rocketseat's Discover](https://app.rocketseat.com.br/journey/discover/overview) or [Eloquent JavaScript](https://eloquentjavascript.net/).
5. **Close the loop with a complete, free full-stack course:** [Full Stack Open in Portuguese](https://fullstackopen.com/ptbr/) (React + Node + database + tests + deployment) or [freeCodeCamp's Certified Full Stack Developer curriculum](https://www.freecodecamp.org/learn/full-stack-developer/) (🇺🇸).
6. **Learn SQL** with [Curso em Vídeo's MySQL course](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) or [SQLBolt](https://sqlbolt.com/) (🇺🇸) and move to [PostgreSQL](https://www.postgresql.org/) in your first real project.
7. **Build 3 complete projects** (front + API + database + deployment) and publish each one with a README, screenshots and a live link. Ideas in the [Hands-on projects](#-hands-on-projects-and-challenges) section.
8. **Join the community and the job boards:** [TabNews](https://www.tabnews.com.br/), the [Rocketseat](https://www.rocketseat.com.br/) Discord and the [frontendbr](https://github.com/frontendbr/vagas) and [backend-br](https://github.com/backend-br/vagas) job repositories. Aim for your first junior job once you have the 3 projects.

Your first full-stack app in 1 minute — a page that calls an API, all in one file:

```bash
mkdir hello-fullstack && cd hello-fullstack
npm init -y
```

```js
// server.js — front-end + API in one file, nothing to install (Node.js 20+)
const { createServer } = require("node:http");

const page = `<!doctype html>
<h1>Hello, full-stack!</h1>
<p id="msg">loading…</p>
<script>
  fetch("/api/hello").then(r => r.json()).then(d => { msg.textContent = d.message; });
</script>`;

createServer((req, res) => {
  if (req.url === "/api/hello") {                     // back-end: API route
    res.writeHead(200, { "Content-Type": "application/json" });
    return res.end(JSON.stringify({ message: "Response from the server 👋" }));
  }
  res.writeHead(200, { "Content-Type": "text/html; charset=utf-8" });
  res.end(page);                                      // front-end: HTML page
}).listen(3000, () => console.log("http://localhost:3000"));
```

```bash
node server.js     # open http://localhost:3000 in the browser
```

## 🎓 Free courses
### In Portuguese
- [Full Stack Open (em português)](https://fullstackopen.com/ptbr/) — University of Helsinki course, translated: React, Node/Express, MongoDB, GraphQL, TypeScript and CI/CD, with graded exercises and certificate. 🆕
- [Curso de HTML5 e CSS3 — Módulo 1 (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n) — Brazil's classic starting point: Gustavo Guanabara teaches HTML and CSS from scratch, with exercises.
- [Curso de JavaScript e ECMAScript para Iniciantes (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1) — JavaScript for people who never programmed, with DOM and events, in Guanabara's didactic pace.
- [Curso de Git e GitHub (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA) — Version control and GitHub Pages without the terminal, ideal for publishing your first projects.
- [Curso de MySQL (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) — Relational databases and SQL from scratch: modeling, SELECT, JOIN and functions.
- [Curso em Vídeo](https://www.cursoemvideo.com/) — Guanabara's free platform with all courses organized, exercises and certificate.
- [Curso de React (Matheus Battisti — Hora de Codar)](https://www.youtube.com/playlist?list=PLnDvRpP8BneyVA0SZ2okm-QBojomniQVO) — React from scratch in Portuguese: components, hooks, routes and API consumption.
- [Curso de JavaScript (Matheus Battisti — Hora de Codar)](https://www.youtube.com/playlist?list=PLnDvRpP8BneysKU8KivhnrVaKpILD3gZ6) — Modern JavaScript fundamentals focused on what you use daily on the front and back end.
- [Curso de Node.js (Victor Lima — Ciência da Computação)](https://www.youtube.com/playlist?list=PLJ_KhUnlXUPtbtLwaxxUxHqvcNQndmI4B) — Node.js and Express in practice: server, routes, database and REST API.
- [Discover (Rocketseat)](https://app.rocketseat.com.br/journey/discover/overview) — Rocketseat's free path covering HTML, CSS, JavaScript and Git fundamentals, with projects. 🆕
- [DIO — bootcamps gratuitos](https://www.dio.me/) — Bootcamps with partner companies (Full-stack, Java, .NET, Python), coding challenges and free certificate. 🆕
- [Escola Virtual — Fundação Bradesco](https://www.ev.org.br/) — Free courses with certificate in HTML, JavaScript, databases and programming logic.
- [freeCodeCamp em português](https://www.freecodecamp.org/portuguese/learn/) — freeCodeCamp's interactive curriculum translated (Responsive Web Design, JavaScript and more), with free certifications.
- [Web Development for Beginners — Microsoft (PT-BR)](https://github.com/microsoft/Web-Dev-For-Beginners/blob/main/translations/pt-BR/README.md) — Microsoft's 12-week curriculum, translated: HTML, CSS and JavaScript through projects.
- [Imersão Dev (Alura)](https://imersao.dev/) — Alura's free recurring immersion to build a web project in a few days. 🆕
- [Docker para desenvolvedores na prática (Full Cycle)](https://www.youtube.com/watch?v=lnzGuiCY4Ns) — Free Docker immersion for developers: containers, Compose and dev environments. 🆕
- [Curso de Programação Web (Cursa)](https://cursa.com.br/) — Free platform with certificate and dozens of HTML, CSS, JavaScript, PHP and database courses.
- [Learn X in Y minutes — JavaScript (PT-BR)](https://learnxinyminutes.com/pt-br/javascript/) — The whole JavaScript syntax in a single commented file, in Portuguese.
- [Refactoring.Guru — Padrões de projeto (PT-BR)](https://refactoring.guru/pt-br/design-patterns) — Design patterns and refactoring explained with illustrations and code examples, in Portuguese.
- [Curso de Git e Github [Completo] — o essencial em 2 horas (Victor Lima)](https://www.youtube.com/watch?v=192HgwRgOYE) — Single 2-hour lesson to master the commit, branch and pull request workflow.
- [Microsoft Learn (PT-BR)](https://learn.microsoft.com/pt-br/training/) — Free learning paths on JavaScript, Node.js, Azure and .NET, with in-browser exercises.

### In English
- [freeCodeCamp — Certified Full Stack Developer](https://www.freecodecamp.org/learn/full-stack-developer/) — New (2025) ~1,800-hour curriculum: HTML, CSS, JavaScript, React, Node, databases and Python, with certification. 🆕 🇺🇸
- [The Odin Project](https://www.theodinproject.com/) — Open, project-based curriculum with an active community; a reference for self-taught developers. 🇺🇸
- [Full Stack Open (Universidade de Helsinque)](https://fullstackopen.com/en/) — Original version of the course; parts 0 to 13 with React, Node, GraphQL, TypeScript, React Native and CI/CD. 🆕 🇺🇸
- [CS50's Web Programming with Python and JavaScript (Harvard)](https://cs50.harvard.edu/web/) — Harvard course: Django, JavaScript, SQL, testing, CI/CD and scalability, with graded projects. 🇺🇸
- [CS50x — Introduction to Computer Science (Harvard)](https://cs50.harvard.edu/x/) — If you have never programmed, start here: computer-science foundations that end with web apps in Flask. 🇺🇸
- [Web Development for Beginners (Microsoft)](https://github.com/microsoft/Web-Dev-For-Beginners) — Original version of Microsoft's curriculum, with 24 lessons and projects. 🇺🇸
- [freeCodeCamp — Responsive Web Design](https://www.freecodecamp.org/learn/2022/responsive-web-design/) — HTML and CSS through projects, with free certification. 🇺🇸
- [freeCodeCamp — Back End Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis/) — Node, Express and MongoDB with API projects and free certification. 🇺🇸
- [Full Stack Web Development for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=nu_pCVPKzTk) — Single video course covering HTML, CSS, JavaScript, Node.js and MongoDB with a complete project. 🇺🇸
- [web.dev Learn (Google)](https://web.dev/learn) — Free courses from the Chrome team: HTML, CSS, forms, accessibility, performance and PWA. 🆕 🇺🇸
- [The Missing Semester of Your CS Education (MIT)](https://missing.csail.mit.edu/) — Terminal, shell, Git, editors and debugging — what nobody teaches and every full-stack developer needs. 🇺🇸
- [MongoDB University](https://learn.mongodb.com/) — Official free MongoDB courses, with completion certificate. 🇺🇸
- [SQLBolt](https://sqlbolt.com/) — Interactive SQL lessons right in the browser; finish in an afternoon. 🇺🇸
- [How to Become a Full-Stack Developer in 2025 (freeCodeCamp Handbook)](https://www.freecodecamp.org/news/become-a-full-stack-developer-and-get-a-job/) — Free handbook with the step-by-step for studying, portfolio and job hunting. 🆕 🇺🇸
- [Learn the MERN Stack in 2025 (freeCodeCamp)](https://www.freecodecamp.org/news/learn-the-mern-stack-in-2025/) — Complete video course: MongoDB, Express, React and Node, from setup to deploying a real app. 🆕 🇺🇸

## 💰 Paid courses
- [Formação Full-Stack (Rocketseat)](https://www.rocketseat.com.br/formacao/fullstack) — From HTML to React and Node with 13 projects and 40+ challenges; community and support included. 🆕 💰
- [Formação Full stack: React com Node.js (Alura)](https://www.alura.com.br/formacao-full-stack-react-node-js) — Alura learning path that starts with React, builds a Node/Express API and ends with testing and deployment. 💰
- [curso.dev (Filipe Deschamps)](https://curso.dev/) — Hands-on full-stack programming course: you build TabNews from scratch with Next.js, Postgres and CI. 🆕 💰
- [Trybe](https://www.betrybe.com/) — Full-stack web development school with a pay-after-hiring model. 💰
- [B7Web (Bonieky Lacerda)](https://b7web.com.br/) — Brazilian platform with front, back and mobile tracks, widely used by beginners. 💰
- [Origamid](https://www.origamid.com/) — Front-end courses (HTML, CSS, JavaScript, React, UI) with top-notch teaching quality. 💰
- [Full Cycle](https://fullcycle.com.br/) — For junior/mid developers: architecture, microservices, Docker, Kubernetes and messaging. 💰
- [Profissão: Desenvolvedor Full Stack Python (EBAC)](https://ebaconline.com.br/full-stack-python) — Long course with portfolio projects and certificate; Python on the back end and JavaScript on the front end. 💰
- [Cod3r](https://www.cod3r.com.br/) — Courses by Leonardo Leitão and team: JavaScript, Node, React, Angular, Java, Docker. 💰
- [Boot.dev](https://www.boot.dev/) — Learn back-end (Go, Python, SQL, Docker) by solving in-browser challenges, gamified. 🆕 💰 🇺🇸
- [Codecademy — Full-Stack Engineer Career Path](https://www.codecademy.com/learn/paths/full-stack-engineer-career-path) — Interactive career path with portfolio projects and certificate. 💰 🇺🇸
- [Master.dev (antigo Frontend Masters)](https://master.dev/) — Video workshops with reference engineers; excellent for going deep on JavaScript, React and Node. 💰 🇺🇸
- [Scrimba](https://scrimba.com/) — Interactive courses where you edit code inside the video; Frontend Developer Career Path. 💰 🇺🇸
- [Zero To Mastery](https://zerotomastery.io/) — Andrei Neagoie's courses: The Complete Web Developer, Node, React, Next.js. 💰 🇺🇸

## 📖 Documentation
- [MDN Web Docs (PT-BR)](https://developer.mozilla.org/pt-BR/) — The definitive reference for HTML, CSS, JavaScript and web APIs, partially translated.
- [MDN — HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP) — How the web talks: methods, headers, status codes, CORS and cookies.
- [Pro Git (livro oficial, PT-BR)](https://git-scm.com/book/pt-br/v2) — The official Git book, free and translated; read chapters 1 to 3 and you know the essentials.
- [React — documentação (PT-BR)](https://pt-br.react.dev/) — Modern React docs, with interactive tutorial and the 'Learn React' section translated. 🆕
- [Next.js — documentação](https://nextjs.org/docs) — Full-stack React framework: routing, Server Components, API routes and deployment. 🆕 🇺🇸
- [Express — documentação (PT-BR)](https://expressjs.com/pt-br/) — Node.js's minimalist web framework; routing, middleware and error-handling guide.
- [Node.js — documentação](https://nodejs.org/docs/latest/api/) — Official reference for Node.js APIs (fs, http, streams, test runner). 🇺🇸
- [Vue.js — documentação (PT-BR)](https://pt.vuejs.org/) — Official Vue 3 docs translated, with a progressive guide from basics to advanced.
- [Django — documentação (PT-BR)](https://docs.djangoproject.com/pt-br/) — Tutorial and reference for the most used Python web framework, in Portuguese.
- [Spring — Guides](https://spring.io/guides/) — Official step-by-step guides to build APIs and web apps with Spring Boot (Java). 🇺🇸
- [Laravel — documentação](https://laravel.com/framework/docs) — Docs of the most popular PHP framework: routing, Eloquent, authentication and queues. 🇺🇸
- [PostgreSQL — documentação](https://www.postgresql.org/docs/) — Complete manual of the relational database most recommended for new projects. 🇺🇸
- [Docker — documentação](https://docs.docker.com/) — Get started, Dockerfile, Compose and best practices to package your application. 🇺🇸
- [Prisma — documentação](https://www.prisma.io/docs) — TypeScript ORM for Postgres, MySQL and SQLite; schema, migrations and typed client. 🇺🇸
- [Tailwind CSS — documentação](https://tailwindcss.com/docs) — Reference for the most used utility-first CSS framework; v4 released in 2025. 🆕 🇺🇸
- [TypeScript — Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) — Official TypeScript handbook, now standard in full-stack JavaScript jobs. 🇺🇸
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — The ten most critical web application security risks; mandatory reading before your first deployment. 🇺🇸
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) — Short guides on doing it right: authentication, passwords, JWT, SQL injection, XSS. 🇺🇸
- [The System Design Primer](https://github.com/donnemartin/system-design-primer) — How systems scale: caching, load balancing, databases, queues — with interview exercises. 🇺🇸
- [DevDocs](https://devdocs.io/) — All documentation (JS, Node, React, Python, SQL…) in one place, with search and offline mode. 🇺🇸
- [Can I use](https://caniuse.com/) — Browser support tables for HTML, CSS and JS features. 🇺🇸
- [Web Almanac (HTTP Archive)](https://almanac.httparchive.org/) — Annual report on the state of the real web: frameworks, performance, accessibility. 🆕 🇺🇸
- [MongoDB — documentação (PT-BR)](https://www.mongodb.com/pt-br/docs/) — Official MongoDB docs translated: CRUD, aggregations and drivers.
- [Python — documentação (PT-BR)](https://docs.python.org/pt-br/3/) — Official Python docs translated, for those choosing Django or FastAPI on the back end.
- [W3Schools](https://www.w3schools.com/) — Quick reference with editable examples of HTML, CSS, JS, SQL and Python. 🇺🇸
- [HTTP Cats](https://http.cat/) — Every HTTP status code illustrated with cats; you will never forget 418 again. 🇺🇸

## 📚 Books
- [Eloquent JavaScript (4ª edição, 2024)](https://eloquentjavascript.net/) — Free, complete JavaScript book, with chapters on the browser and Node.js. 🆕 🇺🇸
- [Eloquente JavaScript (tradução PT-BR)](https://github.com/braziljs/eloquente-javascript) — Community translation (2nd edition) of the book above, by BrazilJS.
- [You Don't Know JS Yet](https://github.com/getify/You-Dont-Know-JS) — Kyle Simpson's free series going deep into scope, closures, objects and async. 🇺🇸
- [The Modern JavaScript Tutorial (javascript.info)](https://javascript.info/) — Free, always-updated tutorial-book: language, DOM, events and networking. 🆕 🇺🇸
- [Free Programming Books — em português](https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-pt_BR.md) — List maintained by the Free Ebook Foundation with free, legal books in Portuguese, by language.
- [Entendendo Algoritmos (Novatec)](https://novatec.com.br/livros/entendendo-algoritmos/) — Illustrated introduction to algorithms and data structures; a foundation for technical interviews. 💰
- [Casa do Código — livros de programação](https://www.casadocodigo.com.br/) — Brazilian publisher with short, practical books on HTML/CSS, JavaScript, Node.js, React, PHP, Java and databases. 💰
- [The Pragmatic Programmer (20th Anniversary Edition)](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) — The classic on the programmer's craft and mindset; Portuguese edition: 'O Programador Pragmático'. 💰 🇺🇸
- [Designing Data-Intensive Applications](https://dataintensive.net/) — Reference on databases, replication and distributed systems; read it at the mid level. 💰 🇺🇸
- [Grokking Algorithms (2ª edição)](https://www.manning.com/books/grokking-algorithms-second-edition) — Original version of 'Entendendo Algoritmos', updated in 2024. 🆕 💰 🇺🇸
- [The Road to React](https://www.roadtoreact.com/) — Hands-on React book, updated with every version; first chapter free. 💰 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Curso em Vídeo](https://www.youtube.com/@cursoemvideo) — Gustavo Guanabara: HTML, CSS, JavaScript, Git, MySQL, PHP — the entry door for millions of developers.
- [Rocketseat](https://www.youtube.com/@rocketseat) — Free lessons, live streams and events on React, Node, TypeScript and career. 🆕
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Gabriel Fróes and Vanessa Weber explain technologies and concepts in short, well-produced videos. 🆕
- [Filipe Deschamps](https://www.youtube.com/@FilipeDeschamps) — Programming explained with rare clarity; creator of TabNews and curso.dev.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Complete free courses on JavaScript, React, Node, PHP, Laravel and Vue.
- [Dev Soutinho (Mario Souto)](https://www.youtube.com/@DevSoutinho) — Front-end and full-stack with live projects, React, Next.js and career.
- [Erick Wendel](https://www.youtube.com/@ErickWendel) — Node.js in depth: streams, performance, testing and internals.
- [Fernanda Kipper](https://www.youtube.com/@kipperdev) — Complete full-stack projects (Java/Spring + React, Node), career and interviews. 🆕
- [Rafaella Ballerini](https://www.youtube.com/@rafaellaballerini) — Git, GitHub, HTML/CSS and the first steps explained calmly for beginners.
- [Full Cycle](https://www.youtube.com/@FullCycle) — Docker, Kubernetes, architecture and free immersions with Wesley Willians. 🆕
- [Otávio Miranda](https://www.youtube.com/@OtavioMiranda) — JavaScript, TypeScript, Node and Python in depth, with long free courses.
- [Michelli Brito](https://www.youtube.com/@MichelliBrito) — Java and Spring Boot for REST APIs, from zero to deployment; Microsoft MVP.
- [Sujeito Programador](https://www.youtube.com/@Sujeitoprogramador) — Hands-on projects with React, Next.js, Node and React Native.
- [Loiane Groner](https://www.youtube.com/@loianegroner) — Free Java, Angular, TypeScript and algorithms courses, with companion repositories.
- [Attekita Dev](https://www.youtube.com/@AttekitaDev) — Career, market and practical tips from someone who hires and mentors developers.
- [Lucas Montano](https://www.youtube.com/@LucasMontano) — Software engineer abroad talking about career, projects and the international market.
- [Alura](https://www.youtube.com/@Alura) — Live streams, immersions and open lessons on the whole web ecosystem.
- [Programador Lhama](https://www.youtube.com/@programadorlhama) — Architecture, best practices and career with a critical view of the market.
- [DevDojo](https://www.youtube.com/@DevDojoBrasil) — Java and Spring in depth, with free marathons.
- [Alura](https://www.youtube.com/@Alura) — Live streams, immersions and open lessons on the whole web ecosystem.

### In English
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Complete 2- to 40-hour courses on practically every web technology, free. 🇺🇸
- [Traversy Media](https://www.youtube.com/@TraversyMedia) — Brad Traversy's crash courses on HTML, CSS, JS, Node, React and full-stack projects. 🇺🇸
- [Fireship](https://www.youtube.com/@Fireship) — 'X in 100 seconds': quick, fun overview of any technology before you study it. 🇺🇸
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) — Kyle Cook explains JavaScript, CSS and React in a simple, direct way. 🇺🇸
- [The Net Ninja](https://www.youtube.com/@NetNinja) — Complete playlists on Node, React, Vue, Firebase, Tailwind and MongoDB. 🇺🇸
- [Kevin Powell](https://www.youtube.com/@KevinPowell) — The channel to really understand CSS: layout, responsiveness and modern features. 🇺🇸
- [Theo — t3.gg](https://www.youtube.com/@t3dotgg) — Strong opinions on the TypeScript/Next.js ecosystem and what to use in 2026. 🆕 🇺🇸
- [Hussein Nasser](https://www.youtube.com/@hnasr) — Back-end engineering in depth: HTTP, databases, proxies and networking. 🇺🇸
- [ByteByteGo](https://www.youtube.com/@ByteByteGo) — Animated system design in short videos, by Alex Xu. 🆕 🇺🇸
- [Programming with Mosh](https://www.youtube.com/@programmingwithmosh) — Beginner tutorials on JavaScript, React, Node, SQL and Python. 🇺🇸
- [Codevolution](https://www.youtube.com/@Codevolution) — Detailed React, Next.js and Node series, one concept per video. 🇺🇸
- [JavaScript Mastery](https://www.youtube.com/@javascriptmastery) — Complete full-stack projects with Next.js, React and modern databases, in long videos. 🆕 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech](https://www.hipsters.tech/) — Alura's podcast on technology and career; TechGuide episodes about full-stack paths.
- [Compilado do Código Fonte TV](https://www.youtube.com/@CompiladoPodcast) — Weekly dev-world news with Gabriel Fróes and Vanessa Weber; also on Spotify and Apple Podcasts. 🆕
- [Fronteiras da Engenharia de Software](https://fronteirases.github.io/) — Brazilian researchers discuss software engineering and practice.
- [Syntax](https://syntax.fm/) — Wes Bos and Scott Tolinski on modern web development, three times a week. 🇺🇸
- [JS Party (Changelog)](https://changelog.com/jsparty) — Weekly panel on JavaScript and the web. 🇺🇸
- [Software Engineering Radio](https://se-radio.net/) — Technical interviews with engineers on architecture, databases and practices. 🇺🇸
- [CodeNewbie](https://www.codenewbie.org/podcast) — Stories from people starting out or switching careers into programming. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Newsletter do Filipe Deschamps](https://filipedeschamps.com.br/newsletter) — Free daily digest of the most relevant tech news, in Portuguese.
- [Blog da Rocketseat](https://www.rocketseat.com.br/blog) — Portuguese articles on React, Node, career and the job market. 🆕
- [Alura — Artigos](https://www.alura.com.br/artigos) — Technical articles in Portuguese on the whole web ecosystem.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Portuguese articles published by the Brazilian community on dev.to.
- [freeCodeCamp News](https://www.freecodecamp.org/news/) — Long tutorials and free handbooks on everything web development. 🇺🇸
- [Smashing Magazine](https://www.smashingmagazine.com/) — In-depth articles on front-end, UX and accessibility. 🇺🇸
- [CSS-Tricks](https://css-tricks.com/) — CSS guides and almanac; the flexbox and grid reference. 🇺🇸
- [web.dev Blog](https://web.dev/blog) — Web platform news straight from the Chrome team. 🆕 🇺🇸
- [JavaScript Weekly](https://javascriptweekly.com/) — Weekly newsletter with what happened in the JavaScript ecosystem. 🇺🇸
- [Node Weekly](https://nodeweekly.com/) — Weekly Node.js newsletter. 🇺🇸
- [Frontend Focus](https://frontendfoc.us/) — Weekly HTML, CSS and front-end newsletter. 🇺🇸
- [Bytes](https://bytes.dev/) — Fun, informative JavaScript newsletter from ui.dev. 🇺🇸
- [TLDR Web Dev](https://tldr.tech/dev) — Daily 5-minute web development digest. 🆕 🇺🇸
- [ByteByteGo Newsletter](https://blog.bytebytego.com/) — System design explained with diagrams, weekly. 🆕 🇺🇸
- [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/) — Gergely Orosz on engineering, career and the tech market; the most-read tech newsletter on Substack. 🆕 🇺🇸

## 🛠️ Tools
### Environment and version control
- [Visual Studio Code](https://code.visualstudio.com/) — The industry-standard free editor, with extensions for everything.
- [Git](https://git-scm.com/) — Version control; indispensable from the first project.
- [GitHub](https://github.com/) — Host code, collaborate and build your public portfolio.
- [Node.js](https://nodejs.org/en) — Server-side JavaScript runtime; always install the LTS version.
- [pnpm](https://pnpm.io/) — Fast, disk-efficient package manager; an alternative to npm. 🇺🇸
- [Bun](https://bun.sh/) — All-in-one JavaScript runtime, bundler and package manager, very fast. 🆕 🇺🇸
- [Docker](https://www.docker.com/) — Containers to run databases and services identically on any machine. 🇺🇸
- [WSL — Subsistema Windows para Linux](https://learn.microsoft.com/pt-br/windows/wsl/install) — Linux environment inside Windows; recommended for web development on Windows.
- [nvm](https://github.com/nvm-sh/nvm) — Manage multiple Node.js versions on the same machine. 🇺🇸

### Front-end
- [React](https://react.dev/) — The most used UI library in the industry. 🇺🇸
- [Next.js](https://nextjs.org/) — Full-stack React framework: SSR, API routes and easy deployment. 🆕 🇺🇸
- [Vue.js](https://vuejs.org/) — Progressive framework with a gentle learning curve; widely used in Brazil. 🇺🇸
- [Angular](https://angular.dev/) — Google's complete framework, strong in large companies and the Java/.NET ecosystem. 🆕 🇺🇸
- [Svelte](https://svelte.dev/) — Compiled framework, no virtual DOM; Svelte 5 released in 2024. 🆕 🇺🇸
- [Vite](https://vite.dev/) — The default build tool for modern front-end projects. 🆕 🇺🇸
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS: style straight in the HTML with classes. 🆕 🇺🇸
- [shadcn/ui](https://ui.shadcn.com/) — Accessible, copy-paste components for React + Tailwind; standard in new projects. 🆕 🇺🇸
- [Chrome DevTools](https://developer.chrome.com/docs/devtools) — Inspect, debug and measure performance right in the browser. 🇺🇸
- [Figma](https://www.figma.com/) — Where the layouts you will implement are designed; free plan. 🇺🇸

### Back-end and databases
- [Express](https://expressjs.com/) — The most used Node.js framework for APIs; Express 5 released in 2024. 🆕 🇺🇸
- [NestJS](https://nestjs.com/) — Opinionated Node framework with modular architecture, very common in job posts. 🇺🇸
- [Fastify](https://fastify.dev/) — Node.js framework focused on performance and schema validation. 🇺🇸
- [Hono](https://hono.dev/) — Lightweight web framework that runs on Node, Bun, Deno and Cloudflare Workers. 🆕 🇺🇸
- [Django](https://www.djangoproject.com/) — 'Batteries included' Python framework: admin, ORM and authentication built in. 🇺🇸
- [Spring Boot](https://spring.io/projects/spring-boot/) — The standard for Java APIs in the Brazilian corporate market. 🇺🇸
- [Laravel](https://laravel.com/) — Modern, productive PHP framework with a large community in Brazil. 🇺🇸
- [PostgreSQL](https://www.postgresql.org/) — Open-source, robust and free relational database; the default choice. 🇺🇸
- [MongoDB](https://www.mongodb.com/) — Document-oriented NoSQL database, common in the MERN stack. 🇺🇸
- [Redis](https://redis.io/) — In-memory store for caching, queues and sessions. 🇺🇸
- [Prisma](https://www.prisma.io/) — ORM for Node/TypeScript with migrations and typed client. 🇺🇸
- [Drizzle ORM](https://orm.drizzle.team/) — Lightweight TypeScript ORM, close to SQL; modern alternative to Prisma. 🆕 🇺🇸
- [DBeaver](https://dbeaver.io/) — Free GUI client for any database. 🇺🇸
- [Supabase](https://supabase.com/) — Postgres with authentication, storage and ready-made APIs; generous free plan. 🆕 🇺🇸
- [Firebase](https://firebase.google.com/) — Google's backend-as-a-service: auth, Firestore and hosting. 🇺🇸

### APIs, testing, quality and deployment
- [Postman](https://www.postman.com/) — Test and document APIs; the corporate standard. 🇺🇸
- [Insomnia](https://insomnia.rest/) — Open-source, lightweight and simple API client. 🇺🇸
- [Bruno](https://www.usebruno.com/) — Offline API client that stores collections as files in your Git repository. 🆕 🇺🇸
- [Swagger / OpenAPI](https://swagger.io/) — Describe and document your API in a standard way. 🇺🇸
- [Vitest](https://vitest.dev/) — Fast, Jest-compatible test runner integrated with Vite. 🆕 🇺🇸
- [Jest](https://jestjs.io/) — The most widespread JavaScript testing framework. 🇺🇸
- [Playwright](https://playwright.dev/) — End-to-end tests on Chromium, Firefox and WebKit, by Microsoft. 🆕 🇺🇸
- [Cypress](https://www.cypress.io/) — End-to-end tests with a visual runner and in-browser debugging. 🇺🇸
- [ESLint](https://eslint.org/) — The standard JavaScript/TypeScript linter. 🇺🇸
- [Prettier](https://prettier.io/) — Automatic code formatter. 🇺🇸
- [Biome](https://biomejs.dev/) — Linter + formatter in a single, very fast tool. 🆕 🇺🇸
- [Vercel](https://vercel.com/) — Deploy front-ends and Next.js in seconds; free plan. 🇺🇸
- [Netlify](https://www.netlify.com/) — Static site hosting and serverless functions with a free plan. 🇺🇸
- [Render](https://render.com/) — Deploy APIs, workers and Postgres databases with a free plan. 🇺🇸
- [Railway](https://railway.com/) — Deploy apps and databases from GitHub, with starter credits. 🆕 🇺🇸
- [Fly.io](https://fly.io/) — Run containers close to users, including in São Paulo. 🇺🇸
- [Cloudflare Pages](https://www.cloudflare.com/products/pages/) — Free front-end hosting with a global CDN and Workers. 🇺🇸
- [GitHub Actions](https://github.com/features/actions) — Free CI/CD for public repositories: run tests and deploy on every push. 🇺🇸
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview) — Audit performance, accessibility and SEO of any page. 🇺🇸

## 🧪 Hands-on projects and challenges
- [Rinha de Backend 2025](https://github.com/zanfranceschi/rinha-de-backend-2025) — Brazilian performance challenge: build a back-end under CPU/memory limits and compare with hundreds of participants. 🆕
- [Rinha de Frontend (Codante)](https://github.com/codante-io/rinha-frontend) — Brazilian front-end challenge: render huge JSON files without freezing the browser. 🆕
- [Codante](https://codante.io/) — Projects and mini-courses with Figma layouts and a ready API for you to build the front and back end. 🆕
- [backend-br/desafios](https://github.com/backend-br/desafios) — Back-end challenges used in hiring processes at Brazilian companies.
- [frontend-challenges (Felipe Fialho)](https://github.com/felipefialho/frontend-challenges) — Collection of real front-end challenges from Brazilian and foreign companies.
- [roadmap.sh — Projects](https://roadmap.sh/projects) — Guided projects by level (beginner to advanced) for front, back and full-stack. 🆕 🇺🇸
- [Frontend Mentor](https://www.frontendmentor.io/) — Front-end challenges with ready-made designs; great for a portfolio. 🇺🇸
- [RealWorld](https://github.com/realworld-apps/realworld) — The 'Medium clone' implemented in dozens of stacks: compare real front-ends and back-ends. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Tutorials to build from scratch an HTTP server, database, shell, framework… 🇺🇸
- [app-ideas](https://github.com/florinpop17/app-ideas) — Application ideas with requirements and difficulty levels to practice. 🇺🇸
- [JavaScript30](https://javascript30.com/) — 30 projects in 30 days with vanilla JavaScript, by Wes Bos. 🇺🇸
- [Codewars](https://www.codewars.com/) — Programming katas in JavaScript, Python and more, with ranking. 🇺🇸
- [Advent of Code](https://adventofcode.com/) — Yearly December challenges; great for practicing logic in any language. 🇺🇸
- [First Contributions](https://github.com/firstcontributions/first-contributions) — Make your first open-source contribution in 10 minutes, with a Portuguese tutorial.
- [CodeCrafters](https://codecrafters.io/) — Rebuild Redis, Git, Docker or an HTTP server step by step; some challenges are free. 🆕 💰 🇺🇸
- [HackerRank](https://www.hackerrank.com/) — Algorithm and SQL exercises used in hiring processes. 🇺🇸
- [NeetCode](https://neetcode.io/) — Algorithm exercise roadmap for interviews, with explanatory videos. 🇺🇸
- [Flexbox Froggy (PT-BR)](https://flexboxfroggy.com/#pt-br) — Game to learn flexbox in 24 levels.

## 🤖 AI in practice
Full-stack is the area where AI assistants changed daily work the most: they generate CRUDs, components and tests in seconds. The risk is just as big — code that "works" with security flaws you cannot read. Use AI to **go faster on what you already understand** and to **learn what you do not understand yet**, never to skip understanding.

**For learning**
- Paste a whole error message (e.g. `TypeError: Cannot read properties of undefined (reading 'map')` or `ECONNREFUSED 127.0.0.1:5432`) with the code snippet and ask: *"explain the likely cause in order of probability and how to confirm each hypothesis"*.
- Ask for a **mental map of a request**: "what happens, step by step, when the user clicks 'Sign in' in a React + Node + Postgres app?". Then compare with what you see in the DevTools *Network* tab.
- Ask it to **review your code the way a senior would** — naming, error handling, input validation, N+1 queries — and rewrite it yourself.
- Ask for **exercises with answer keys** on the week's topic (JOINs, `async/await`, React hooks, JWT) and only look at the answer after trying.
- Use study mode: *"don't give me the code; ask me questions until I reach the solution"*.

**For work**
- In the editor, [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) or [Gemini Code Assist](https://codeassist.google/) for autocomplete, test generation and explaining legacy code. In the terminal, [Claude Code](https://code.claude.com/docs/en/overview) for bigger tasks: "add pagination to the `/products` endpoint, with tests".
- To prototype interfaces, [v0](https://v0.app/) generates React + Tailwind from a prompt; [bolt.new](https://bolt.new/) builds a whole app in the browser. Treat the result as a draft: read, understand and refactor before shipping.
- Good daily uses: writing the SQL migration from the table description, generating test data (*seed*), converting a `curl` into code, writing the README and the OpenAPI documentation of your API.
- After **every** accepted suggestion: run the tests, the linter and open the application. If you cannot explain a line, do not commit it.

**Limits and good practices**
- AI **makes up packages and APIs** that do not exist (and criminals register those names on npm — so-called *slopsquatting*). Confirm in the npm registry and in the official docs before installing.
- Security is not free: explicitly ask for input validation, hashed passwords (bcrypt/argon2), parameterized queries and XSS/CSRF protection, and check against the [OWASP Top 10](https://owasp.org/www-project-top-ten/).
- Never paste secrets (`.env`, API keys, customer data) into tools without your company's policy.
- "Vibe coding" works for prototypes, not for production or interviews: whoever hires you will ask *why* the code looks the way it does.

**Full-stack + AI as a product.** Knowing how to put an LLM inside an application (chat, semantic search, automations) has become a differentiator in full-stack jobs. Start here:
- [GitHub Copilot](https://github.com/features/copilot) — AI autocomplete and chat in the editor; free for students and with a free tier. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — VS Code-based editor with AI built into the workflow. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: implements features, writes tests and explains legacy code. 🆕 🇺🇸
- [Gemini Code Assist](https://codeassist.google/) — Google's coding assistant with a free tier for individual use. 🆕 🇺🇸
- [v0 (Vercel)](https://v0.app/) — Generate React + Tailwind interfaces from a prompt and export the code. 🆕 🇺🇸
- [bolt.new](https://bolt.new/) — In-browser environment that generates and runs full-stack apps with AI. 🆕 🇺🇸
- [Vercel AI SDK](https://ai-sdk.dev/) — TypeScript SDK to put LLMs in your app: streaming, tools and agents. 🆕 🇺🇸
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) — Open standard to connect AI assistants to your APIs, databases and tools. 🆕 🇺🇸
- [Ollama](https://ollama.com/) — Run open-source models (Llama, Gemma, Qwen) locally and integrate via API. 🆕 🇺🇸

## 📜 Certifications
There is no official "full-stack developer" certification: the Brazilian market assesses **published portfolio, live projects and hands-on skill**. What weighs on a résumé are **cloud** certifications (where your application will run) and completion certificates from recognized courses — according to Robert Half's 2026 Salary Guide, 48% of technology hiring managers in Brazil pay more to candidates with certifications or specialized knowledge.
- [freeCodeCamp — certificações gratuitas](https://www.freecodecamp.org/learn/) — Responsive Web Design, JavaScript, Front End Libraries, Back End and the new Full Stack Developer: all free and verifiable. 🆕 🇺🇸
- [Meta Front-End Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-front-end-developer) — Meta's professional certificate: HTML, CSS, JavaScript and React; free to audit. 💰 🇺🇸
- [Meta Back-End Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-back-end-developer) — Python, Django, APIs and databases, with a capstone project. 💰 🇺🇸
- [IBM Full Stack Software Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer) — HTML, JavaScript, React, Node, Python, Docker and Kubernetes with a cloud focus. 💰 🇺🇸
- [AWS Certified Cloud Practitioner](https://aws.amazon.com/pt/certification/certified-cloud-practitioner/) — Entry point to cloud; often requested in full-stack jobs that deploy on AWS. 💰
- [AWS Certified Developer – Associate](https://aws.amazon.com/pt/certification/certified-developer-associate/) — Certification for people who develop and deploy applications on AWS. 💰
- [Microsoft Certified: Azure Developer Associate (AZ-204)](https://learn.microsoft.com/pt-br/credentials/certifications/azure-developer/) — Building solutions on Azure; common in .NET-ecosystem companies. 💰
- [Google Associate Cloud Engineer](https://cloud.google.com/learn/certification/cloud-engineer) — Google Cloud's entry-level certification for deploying and operating applications. 💰 🇺🇸
- [CKAD — Certified Kubernetes Application Developer](https://www.cncf.io/training/certification/ckad/) — For people already using containers who want to prove Kubernetes deployment skills. 💰 🇺🇸
- [Certificados gratuitos da DIO](https://www.dio.me/) — Bootcamps with companies and free completion certificates.
- [Certificados da Escola Virtual Bradesco](https://www.ev.org.br/) — Free, recognized certificates in programming and web courses.

## 💼 Career and jobs
**How much it pays:** [Robert Half's 2026 Salary Guide](https://www.roberthalf.com/br/pt/insights/guia-salarial/tecnologia) places the full-stack developer at **R$ 6,050 to R$ 8,750 (junior)**, **R$ 9,550 to R$ 15,900 (mid-level)** and **R$ 12,450 to R$ 20,950 (senior)** per month (CLT employment). The [Código Fonte TV 2025 Salary Survey](https://pesquisa.codigofonte.com.br/2025) (12.5k answers) recorded an overall average of **R$ 8,886 (CLT)** and **R$ 13,344 (contractor/PJ)**, with remote work still the majority. International remote jobs pay in dollars but require fluent English.

**What job posts ask for:** JavaScript/TypeScript, React (or Angular/Vue), Node.js (or Java/Spring, Python, PHP/Laravel, C#/.NET), SQL, Git, REST APIs, testing and Docker/cloud basics. Tip: in the GitHub job repositories below, search open issues for "full stack" and "júnior".
- [Pesquisa Salarial de Programadores 2026 (Código Fonte TV)](https://pesquisa.codigofonte.com.br/2026) — Brazil's largest developer salary survey, filterable by area (full-stack), seniority, CLT/PJ and region. 🆕
- [Pesquisa Salarial de Programadores 2025 (Código Fonte TV)](https://pesquisa.codigofonte.com.br/2025) — Previous edition (12,510 answers): CLT average R$ 8.9k and PJ R$ 13.3k; good for comparing trends. 🆕
- [Guia Salarial 2026 — Tecnologia (Robert Half)](https://www.roberthalf.com/br/pt/insights/guia-salarial/tecnologia) — Salary ranges by role and seniority; junior Full-Stack from R$ 6,050 to R$ 8,750, mid from R$ 9,550 to R$ 15,900. 🆕
- [Robert Half — salário de Desenvolvedor(a) Full-Stack Pleno](https://www.roberthalf.com/br/pt/vagas-detalhes/desenvolvedora-full-stack-pleno) — Role-specific page with 2026 ranges and variation by city. 🆕
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Most used and wanted technologies worldwide; JavaScript, SQL, Node and React remain on top. 🆕 🇺🇸
- [State of JavaScript 2024](https://2024.stateofjs.com/en-US/) — Annual JS ecosystem survey: frameworks, tools and salaries. 🆕 🇺🇸
- [Programathor](https://programathor.com.br/) — Tech jobs in Brazil filterable by stack (Node, React, Java, Python).
- [GeekHunter](https://www.geekhunter.com/pt) — Platform where companies make offers to developers; shows salary ranges in job posts.
- [Coodesh](https://coodesh.com/) — Tech jobs with standardized hiring processes and technical challenges.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [Gupy](https://portal.gupy.io/) — Portal used by large Brazilian companies; filter by 'desenvolvedor full stack'.
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Front-end jobs posted as GitHub issues.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end jobs (Node, Java, Python, Go) on GitHub.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — React and React Native jobs on GitHub.
- [RemoteOK — vagas full stack](https://remoteok.com/remote-full-stack-jobs) — International remote full-stack jobs, many paid in dollars. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete technical interview prep: algorithms, system design and behavioral. 🇺🇸
- [Front End Interview Handbook](https://www.frontendinterviewhandbook.com/) — Front-end interview questions and answers (HTML, CSS, JS). 🇺🇸
- [Robert Half — salário de Desenvolvedor(a) Full-Stack Júnior](https://www.roberthalf.com/br/pt/vagas-detalhes/desenvolvedora-full-stack-junior) — Entry-level range updated for 2026, useful for negotiating your first job. 🆕
- [Robert Half — salário de Desenvolvedor(a) Full-Stack Sênior](https://www.roberthalf.com/br/pt/vagas-detalhes/desenvolvedora-full-stack-senior) — Senior range (R$ 12,450 to R$ 20,950) to know where the career can go. 🆕
- [Desenvolvedor Full Stack: salários e dicas de carreira (GeekHunter)](https://www.geekhunter.com/pt/blog/desenvolvedor-full-stack/) — Article with a salary overview by seniority and what companies ask for.
- [Quanto ganha um desenvolvedor full stack no Brasil em 2026 (Growdev)](https://growdev.com.br/quanto-ganha-um-desenvolvedor-full-stack/) — Compilation of sources (CAGED, Glassdoor, Robert Half) with ranges per level. 🆕
- [Programador full stack: como é o dia a dia (Rocketseat)](https://www.rocketseat.com.br/blog/artigos/post/rotina-programador-full-stack) — What is expected of a full-stack developer in real work, before choosing the area. 🆕

## 👥 Communities
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical-content community created by Filipe Deschamps; open source and built with Next.js + Postgres.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open-source community with an active Discord, mentoring and projects.
- [Rocketseat — comunidade](https://www.rocketseat.com.br/) — One of Latin America's largest developer communities, with an open Discord.
- [Frontend BR — fórum](https://github.com/frontendbr/forum) — Brazilian front-end forum on GitHub Discussions.
- [Backend BR](https://github.com/backend-br) — Brazilian back-end organization: jobs, challenges and discussions.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and job posts.
- [r/brdev](https://www.reddit.com/r/brdev/) — Brazilian developers' subreddit: career, salaries and venting.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups by technology.
- [PrograMaria](https://www.programaria.org/) — Community and courses for women in tech.
- [{reprograma}](https://reprograma.com.br/) — Free programming bootcamps for women, focused on employability.
- [WoMakersCode](https://www.womakerscode.org/) — Community that trains women in tech with free bootcamps.
- [freeCodeCamp Forum](https://forum.freecodecamp.org/) — International forum with a Portuguese section; ask questions about the courses. 🇺🇸
- [r/webdev](https://www.reddit.com/r/webdev/) — The largest web development subreddit. 🇺🇸
- [Dev.to](https://dev.to/) — Global community of programming articles and discussions. 🇺🇸

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
