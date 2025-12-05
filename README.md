# Projeto de Login e Dashboard em Angular

Esta é uma aplicação simples desenvolvida com **Angular 17** para demonstrar um fluxo completo de autenticação de usuário, incluindo uma tela de login com validação, uma página de dashboard protegida e simulação de comunicação com um backend.

## ✨ Funcionalidades

* **Tela de Login:** Formulário com validação de campos (email e senha).
* **Dashboard Protegido:** Página acessível apenas para usuários autenticados.
* **Simulação de Autenticação:** Um serviço (`AuthService`) simula a validação de credenciais.
* **Rotas Protegidas:** Uso de `CanActivate` (Route Guard) para proteger a rota do dashboard.
* **Logout:** Funcionalidade para encerrar a sessão do usuário.

## 🚀 Tecnologias Utilizadas

* Angular 17
* TypeScript
* SCSS para estilização
* RxJS para programação reativa

## ⚙️ Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Parllon/fokus_parllon.git
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

3.  **Execute a aplicação:**
    ```bash
    ng serve
    ```

4.  Abra seu navegador e acesse `http://localhost:4200/`.