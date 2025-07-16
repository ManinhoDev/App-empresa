# 🛡️ Projeto Angular - Tela de Login com AuthGuard

Este é um projeto Angular desenvolvido como exercício prático de autenticação com uso de formulário de login, service de autenticação e rota protegida com `AuthGuard`.

## 📌 Objetivo

Criar um sistema básico de autenticação contendo:

- Formulário de login validando usuário e senha via service.
- Rota protegida (`/painel-controle`) acessível apenas por usuários autenticados.
- Redirecionamento automático com base na autenticação.
- Visualização limpa e objetiva, com uso mínimo de CSS.

---

## 🧱 Tecnologias Utilizadas

- Angular 19 Standalone
- TypeScript
- HTML / CSS

---

## ✅ Funcionalidades

- Tela de login simples com campos de **usuário** e **senha**.
- Validação básica via `AuthService`.
- Redirecionamento para painel de controle ao login válido.
- `AuthGuard` protegendo a rota `/painel-controle`.
- Mensagens de erro ao tentar acessar a rota sem autenticação.

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
