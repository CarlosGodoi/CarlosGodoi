<div align="center">
  <img
    src="./assets/carlos-godoi-matrix-readme.svg"
    alt="Carlos Eduardo Godoi - Front-End Developer"
    width="100%"
  />
</div>

<br />
<br />

<div align="center">

[ ABOUT ](#about) •
[ SKILLS ](#skills) •
[ ENGINEERING ](#engineering) •
[ PROJECTS ](#projects) •
[ STATS ](#github-stats) •
[ CONTACT ](#contact)

</div>

---

<a id="about"></a>

## `> ./about`

Sou **Desenvolvedor Front-End** com **3 anos de experiência**, atuando
principalmente com **React, TypeScript e Next.js** na construção de
aplicações web modernas, responsivas e escaláveis.

Também possuo experiência como **Fullstack Developer**, desenvolvendo
APIs REST e serviços backend utilizando **Node.js, Express e Fastify**,
além de trabalhar com bancos de dados relacionais e Prisma.

Tenho experiência com desenvolvimento de interfaces, integração com APIs,
validação de dados, gerenciamento de estado, testes e aplicação de boas
práticas de desenvolvimento.

Meu foco está em escrever código **limpo, organizado e manutenível**,
buscando equilibrar qualidade técnica, experiência do usuário e
necessidades do produto.

---

<a id="skills"></a>

## `> ./skills`

### Front-End

<div>

<img src="https://skillicons.dev/icons?i=javascript,typescript,react,next,vite,html,css,tailwind,sass,materialui,styledcomponents,figma" />

</div>

### Back-End

<div>

<img src="https://skillicons.dev/icons?i=nodejs,express,fastify,prisma,nestjs" />

</div>

### Database

<div>

<img src="https://skillicons.dev/icons?i=postgres,mysql" />

</div>

### Testing & Tools

<div>

<img src="https://skillicons.dev/icons?i=git,github,docker,vscode,postman,jest,vitest" />

</div>

<br />

| Área | Tecnologias |
| --- | --- |
| **Front-End** | React, Next.js, TypeScript, JavaScript |
| **UI** | Tailwind CSS, Material UI, Sass, Styled Components |
| **Forms & Validation** | React Hook Form, Zod, Yup |
| **State Management** | Zustand, Context API |
| **Data Fetching** | Axios, React Query |
| **Back-End** | Node.js, Express, Fastify |
| **Database** | PostgreSQL, MySQL, Prisma |
| **Testing** | Jest, Vitest, Testing Library |
| **APIs** | REST |

---

<a id="engineering"></a>

## `> ./engineering`

### Engineering Focus

```text
┌──────────────────────────────────────────────────────────┐
│ ENGINEERING FOCUS                                        │
├──────────────────────────────────────────────────────────┤
│                                                          │
│ FRONTEND       React / Next.js / TypeScript              │
│ ARCHITECTURE   Clean Code / SOLID / DRY                  │
│ API            REST / Axios / React Query                │
│ FORMS          React Hook Form / Zod / Yup               │
│ TESTING        Jest / Vitest / Testing Library           │
│ BACKEND        Node.js / Express / Fastify               │
│ DATABASE       PostgreSQL / MySQL / Prisma               │
│ UI             Tailwind / Material UI / Shadcn UI        │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

### Práticas

- Componentização e reutilização
- Clean Code
- SOLID
- DRY
- Arquitetura organizada
- Integração com APIs REST
- Validação de dados
- Testes unitários
- HTML semântico
- Acessibilidade
- Performance e experiência do usuário

---

<a id="currently-building"></a>

## `> ./currently-building`

### 🚀 Atualmente construindo

**LibriX**

Sistema de gerenciamento de biblioteca desenvolvido com foco em
autenticação, controle de acesso, gerenciamento de livros e empréstimos,
além de integração com IA.

**Portfolio v2**

Portfólio pessoal desenvolvido com Next.js, Tailwind CSS e Shadcn UI,
com foco em apresentação profissional, projetos e experiência técnica.

### Próximos objetivos

- Evoluir projetos pessoais.
- Aprimorar arquitetura e testes.
- Explorar recursos modernos do ecossistema React.
- Melhorar performance e experiência do usuário.
- Continuar aprofundando conhecimentos em desenvolvimento Fullstack.

---

<a id="projects"></a>

## `> ./projects`

### 📚 LibriX

Sistema de gerenciamento de biblioteca desenvolvido com foco em
arquitetura, autenticação, controle de acesso e integração com IA.

**Stack**

`Next.js` `React` `TypeScript` `Node.js` `Express` `Prisma` `PostgreSQL`

**Principais funcionalidades**

- Autenticação e autorização baseada em roles.
- Gerenciamento de usuários.
- Gerenciamento de livros.
- Controle de empréstimos.
- APIs REST.
- Sistema de recomendações de livros.
- Chat integrado com IA.
- Interface responsiva.

**Links**

[Frontend](COLOQUE_AQUI_O_LINK_DO_FRONTEND) •
[Backend](COLOQUE_AQUI_O_LINK_DO_BACKEND)

---

### 💻 Portfolio v2

Meu portfólio pessoal desenvolvido com foco em apresentar minha
experiência, projetos e conhecimentos técnicos.

**Stack**

`Next.js` `React` `TypeScript` `Tailwind CSS` `Shadcn UI`

**Destaques**

- Design responsivo.
- Componentização.
- Internacionalização.
- Interface moderna.
- Apresentação de projetos.
- Integração com recursos de IA.

🌐 [Acessar Portfolio](https://portifolio-v2-coral.vercel.app/)

---

<a id="architecture"></a>

## `> ./architecture`

### LibriX Architecture

```text
                         ┌─────────────────────┐
                         │      NEXT.JS        │
                         │   React / TypeScript │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │      REST API       │
                         │   Node.js / Express │
                         └──────────┬──────────┘
                                    │
                  ┌─────────────────┼─────────────────┐
                  │                 │                 │
                  ▼                 ▼                 ▼
           ┌────────────┐    ┌────────────┐    ┌────────────┐
           │   PRISMA   │    │    AUTH    │    │  AI LAYER  │
           └──────┬─────┘    └────────────┘    └────────────┘
                  │
                  ▼
           ┌────────────┐
           │ POSTGRESQL │
           └────────────┘
```

### Architecture & Development

O projeto foi estruturado buscando separar responsabilidades entre
interface, camada de API, autenticação, persistência de dados e recursos
de inteligência artificial.

Entre os principais conceitos utilizados estão:

- Clean Architecture
- SOLID
- REST API
- RBAC
- Prisma ORM
- PostgreSQL
- Autenticação baseada em cookies
- Integração com serviços de IA
- Testes unitários
- Separação entre Front-End e Back-End

---

<a id="github-stats"></a>

## `> ./github-stats`

<div align="center">

<img
  height="180"
  src="https://github-readme-stats.vercel.app/api?username=CarlosGodoiB&show_icons=true&theme=matrix&hide_border=true"
  alt="GitHub Stats"
/>

<img
  height="180"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=CarlosGodoiB&layout=compact&theme=matrix&hide_border=true"
  alt="Top Languages"
/>

</div>

<br />

<div align="center">

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=CarlosGodoiB&theme=2077"
  alt="GitHub Profile Details"
/>

</div>

---

<a id="contact"></a>

## `> ./contact`

<div align="center">

Se quiser trocar uma ideia sobre desenvolvimento, tecnologia ou
oportunidades profissionais, fique à vontade para entrar em contato.

<br />

<a href="https://www.linkedin.com/in/carlosegodoi" target="_blank">
  <img
    src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
    alt="LinkedIn"
  />
</a>

<a href="mailto:edu-godoi@hotmail.com">
  <img
    src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"
    alt="Email"
  />
</a>

<a href="https://portifolio-v2-coral.vercel.app/" target="_blank">
  <img
    src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"
    alt="Portfolio"
  />
</a>

</div>

---

<div align="center">

```text
> system.status

CARLOS SYSTEM
STATUS: ONLINE

"Keep learning. Keep building. Keep improving."

< / >
```

</div>
