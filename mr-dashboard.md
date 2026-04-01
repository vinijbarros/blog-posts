---
title: Dashboard
date: 2025-11-07
excerpt: Evolução do dashboard protegido do projeto Mamãe Review.
tags: [Next.js, TypeScript, Firebase, Firestore, TailwindCSS]
---

# Mamãe Review Dashboard

## PT-BR

No Mamãe Review, implementei o dashboard, uma página protegida exibida após o login e responsável por centralizar informações e ações do usuário.

O principal desafio foi criar uma interface segura, fluida e responsiva, com carregamento eficiente dos dados do Firestore e feedback visual durante todo o processo.

### Stack utilizada

- Next.js 15 com App Router
- Firebase Auth e Firestore
- React Context API
- TypeScript
- Tailwind CSS com Shadcn/ui

Também desenvolvi um componente `ProtectedRoute` para garantir a autenticação antes da renderização e evitar o flash de conteúdo protegido.

O fluxo de autenticação foi estruturado para que, após o login, o Firebase atualize o estado, o usuário seja redirecionado ao dashboard e os dados sejam carregados de forma assíncrona, com tratamento de erros e fallbacks.

O resultado é uma página sólida, que combina segurança, desempenho e uma experiência de usuário consistente, representando mais um passo importante na evolução do projeto.

## EN

In Mamãe Review, I implemented the dashboard, a protected page displayed after login that centralizes user information and actions.

The main challenge was to create a secure, fluid, and responsive interface, with efficient Firestore data loading and clear visual feedback throughout the experience.

### Tech stack

- Next.js 15 with App Router
- Firebase Auth and Firestore
- React Context API
- TypeScript
- Tailwind CSS with Shadcn/ui

I also developed a `ProtectedRoute` component to ensure authentication before rendering and prevent any flash of protected content.

The authentication flow was structured so that, after login, Firebase updates the state, the user is redirected to the dashboard, and the data is loaded asynchronously with proper error handling and fallbacks.

The result is a solid page that combines security, performance, and a consistent user experience, marking another important step forward in the project.
