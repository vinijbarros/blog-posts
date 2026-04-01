---
title: Habit-Tracker
date: 2026-04-01
excerpt: App de Habitos
tags: [NodeJS, typescript, Prisma, JWT]
---

# Conteúdo do Post

🇧🇷 Habit-tracker 
Desenvolvi um projeto de Habit Tracker com foco em organização pessoal, consistência e visualização de progresso ao longo do tempo.

A aplicação permite que o usuário crie uma conta, faça login com autenticação segura e gerencie seus hábitos de forma prática. Além do cadastro e edição de hábitos, o sistema também oferece acompanhamento diário, definição de frequências diferentes (diária, semanal e personalizada) e um resumo visual de desempenho por período, facilitando a análise da evolução e da constância nas metas.

Na arquitetura, o projeto foi organizado em formato de monorepo, separando frontend e backend para deixar a aplicação mais escalável e bem estruturada. No backend, utilizei Node.js com Express e TypeScript para construção da API, Prisma como ORM, PostgreSQL como banco de dados, JWT para autenticação, bcrypt para hash de senhas e Zod para validação de dados. No frontend, desenvolvi a interface com React, Vite e TypeScript, utilizando Tailwind CSS para estilização, React Router para navegação, Axios para comunicação com a API e Recharts para os gráficos de resumo. O projeto também conta com suporte a Docker para facilitar a execução em ambiente local e deploy.

Foi um projeto muito importante para praticar conceitos de arquitetura full stack, autenticação, modelagem de dados, consumo de API, visualização de métricas e organização de código em um cenário mais próximo do mercado.

🇬🇧 🇺🇸 Habit-tracker
I developed a Habit Tracker project focused on personal organization, consistency, and progress visualization over time.

The application allows users to create an account, log in with secure authentication, and manage their habits in a practical way. In addition to creating and editing habits, the system also offers daily tracking, different frequency settings (daily, weekly, and custom), and a visual performance summary by period, making it easier to analyze progress and consistency in achieving goals.

From an architectural perspective, the project was organized as a monorepo, separating the frontend and backend to make the application more scalable and well-structured. On the backend, I used Node.js with Express and TypeScript to build the API, Prisma as the ORM, PostgreSQL as the database, JWT for authentication, bcrypt for password hashing, and Zod for data validation. On the frontend, I built the interface with React, Vite, and TypeScript, using Tailwind CSS for styling, React Router for navigation, Axios for API communication, and Recharts for the summary charts. The project also includes Docker support to simplify local development and deployment.

This was a very important project for practicing full-stack architecture concepts, authentication, data modeling, API consumption, metrics visualization, and code organization in a scenario closer to real-world market needs.