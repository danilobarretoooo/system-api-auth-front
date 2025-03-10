# 🎨 System API Auth - Frontend (Angular)

Este é o frontend da aplicação **System API Auth**, desenvolvido com **Angular**. Ele permite a interação com a API de autenticação e gerenciamento de usuários, fornecendo uma interface moderna e responsiva.

Atualmente, a aplicação conta com:

- 🏠 **Tela de Login e Registro**
- 🔑 **Autenticação JWT integrada à API**
- 👤 **Gerenciamento de Usuários**
- 🚀 **Estrutura pronta para expansão**

---

## 🚀 Tecnologias Utilizadas

- **Angular (Última versão estável)**
- **TypeScript**
- **Angular Material (UI)**
- **RxJS**
- **JWT para autenticação**
- **SCSS para estilização**

---

## 📦 Como Rodar o Projeto

### Pré-requisitos

- **Node.js** instalado (versão recomendada: LTS)
- **Angular CLI** instalado

### Passos para execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/system-api-auth-frontend.git
   cd system-api-auth-frontend

2. Instale as dependências:
   ```sh
    npm install

3. Configure a URL da API no arquivo src/environments/environment.ts:
   ```sh
    export const environment = {
    production: false,
    apiUrl: 'http://localhost:8080'
    };
4. Execute o projeto:
   ```sh
    ng serve

5. Acesse no navegador:
   ```sh
    http://localhost:4200
