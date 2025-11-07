---
title: Dashboard
date: 2025-11-07
excerpt: Uma breve descrição do post
tags: [tech, javascript, typescript, Firebase]
---

# Conteúdo do Post

🇧🇷 Atualização do Projeto — Mamãe Review
No Mamãe Review, implementei o dashboard — uma página protegida exibida após o login, responsável por centralizar informações e ações do usuário. O principal desafio foi criar uma interface segura, fluida e responsiva, com carregamento eficiente dos dados do Firestore e feedback visual durante todo o processo. A stack utilizada inclui Next.js 15 (App Router), Firebase Auth + Firestore, React Context API, TypeScript e TailwindCSS com Shadcn/ui. Também desenvolvi um componente ProtectedRoute para garantir a autenticação antes da renderização e evitar o “flash” de conteúdo protegido. O fluxo de autenticação foi estruturado para que, após o login, o Firebase atualize o estado, o usuário seja redirecionado ao dashboard e os dados sejam carregados de forma assíncrona, com tratamento de erros e fallbacks. O resultado é uma página sólida, que combina segurança, desempenho e uma experiência de usuário consistente — mais um passo importante na evolução do projeto.

🇬🇧 🇺🇸 Project Update — Mamãe Review
In Mamãe Review, I implemented the dashboard — a protected page displayed after login, responsible for centralizing user information and actions. The main challenge was to create a secure, fluid, and responsive interface with efficient Firestore data loading and clear visual feedback throughout the process.

The tech stack includes Next.js 15 (App Router), Firebase Auth + Firestore, React Context API, TypeScript, and TailwindCSS with Shadcn/ui. I also developed a ProtectedRoute component to ensure authentication before rendering and to prevent any “flash” of protected content.

The authentication flow was structured so that, after login, Firebase updates the state, the user is redirected to the dashboard, and the data is loaded asynchronously with proper error handling and fallbacks.

The result is a solid page that combines security, performance, and a consistent user experience — another important step forward in the project’s development.