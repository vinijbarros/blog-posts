---
title: Login Page
date: 2025-10-31
excerpt: Ajustes no fluxo de autenticação do projeto Mamãe Review.
tags: [Next.js, TypeScript, Firebase, Auth, TailwindCSS]
---

# Mamãe Review Login

## PT-BR

Como comentei no post anterior, estou desenvolvendo uma aplicação web completa para avaliação de produtos por mães, utilizando uma arquitetura moderna com Next.js 15, React, TypeScript e Firebase.

O sistema permite que as usuárias façam login tanto com email e senha quanto por meio de suas contas do Google, oferecendo uma experiência de uso fluida e segura.

### Stack utilizada

- Frontend com Next.js 15, App Router, React 18 e TypeScript
- Banco de dados com Firestore
- Estilização com Tailwind CSS e componentes Shadcn/ui
- Deploy na Vercel com integração ao GitHub
- Autenticação com Firebase Auth, Google OAuth e email/senha

Tenho priorizado o uso de ferramentas gratuitas neste momento para manter o foco no aprendizado e na viabilidade do projeto.

A tela de autenticação passou recentemente por alguns ajustes importantes. Inicialmente, surgiram erros quando o usuário fazia cadastro sem usar Gmail: a página não atualizava corretamente e ele ficava preso, sem conseguir voltar à página principal. Em outros casos, o login com Gmail funcionava, mas o sistema não reconhecia o usuário como autenticado.

Depois de investigar melhor o funcionamento do Firebase Auth, consegui corrigir esses problemas.

O desenvolvimento desse projeto tem sido um grande desafio, especialmente por eu estar explorando ferramentas e recursos que ainda não dominava. Ao mesmo tempo, tem sido muito gratificante acompanhar a evolução e ver o projeto ganhando forma a cada nova etapa.

## EN

As I mentioned in my previous post, I have been developing a complete web application for product reviews made by mothers, using a modern architecture with Next.js 15, React, TypeScript, and Firebase.

The system allows users to log in either with email and password or through their Google accounts, providing a smooth and secure experience.

### Tech stack

- Frontend with Next.js 15, App Router, React 18, and TypeScript
- Firestore as the database
- Tailwind CSS with Shadcn/ui components for styling
- Deployment on Vercel integrated with GitHub
- Authentication with Firebase Auth, Google OAuth, and email/password

For now, I have been prioritizing free tools to keep the project focused on learning and practical viability.

The authentication screen recently went through some important fixes. At first, there were issues when users signed up without using Gmail: the page did not refresh properly, and they became stuck without being able to return to the main page. In other cases, Google login worked, but the system did not recognize the user as authenticated.

After taking a deeper look into how Firebase Auth works, I managed to fix those problems.

Developing this project has been a major challenge, especially because I am exploring tools and resources that were still new to me. At the same time, it has been very rewarding to watch the project evolve and take shape with each new step.
