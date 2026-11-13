# DSM | Site Institucional

Site institucional desenvolvido como atividade acadêmica da **Fatec**, com o objetivo de apresentar o curso de **Desenvolvimento de Software Multiplataforma (DSM)** e disponibilizar páginas de navegação para login e cadastro.

## 📌 Sobre o Projeto

O projeto apresenta informações sobre o curso de DSM, destacando seus objetivos, áreas de conhecimento, tecnologias e práticas de desenvolvimento.

A aplicação também possui páginas de login, cadastro e tratamento de erros 404, utilizando um servidor Node.js com Express para disponibilizar os arquivos HTML e os recursos estáticos.

## ✨ Funcionalidades

- **Página inicial:** apresentação do curso de Desenvolvimento de Software Multiplataforma.
- **Página de login:** interface com campos de e-mail e senha.
- **Página de cadastro:** interface com campos de e-mail, senha e confirmação de senha.
- **Página 404:** exibição de uma mensagem personalizada para páginas não encontradas.
- **Navegação:** links para alternar entre as páginas.
- **Servidor Express:** disponibilização das páginas e dos arquivos estáticos.

> **Observação:** as interfaces de login e cadastro são apenas visuais nesta versão. A autenticação e o armazenamento de usuários ainda não estão implementados.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|---|---|
| HTML5 | Estruturação das páginas |
| CSS3 | Estilização e layout |
| JavaScript | Execução do servidor |
| Node.js | Ambiente de execução |
| Express.js | Servidor e gerenciamento de rotas |
| dotenv | Gerenciamento de variáveis de ambiente |

## 📂 Estrutura do Projeto

```text
Small-Fatec-site-/
│
├── public/
│   ├── assets/
│   │   ├── css/
│   │   │   └── main.css
│   │   └── img/
│   │       ├── logo_dsm_transparente.png
│   │       ├── logo_fatec_transparente.png
│   │       └── logo_cps_transparente.png
│   │
│   └── pages/
│       ├── index.html
│       ├── login.html
│       ├── cadastro.html
│       └── 404.html
│
├── server.js
├── package.json
└── package-lock.json
```

## ⚙️ Como Executar

### 1. Pré-requisitos

- [Node.js](https://nodejs.org/)
- npm (instalado junto com o Node.js)

### 2. Clonar o repositório

```bash
git clone https://github.com/EnzoSuzukiProkopas/Small-Fatec-site-.git
```

### 3. Acessar a pasta

```bash
cd Small-Fatec-site-
```

### 4. Instalar as dependências

```bash
npm install
```

### 5. Configurar as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```env
PORT=3000
```

### 6. Iniciar o servidor

**Modo desenvolvimento:**

```bash
npm run dev
```

**Modo padrão:**

```bash
npm start
```

Após iniciar o servidor, acesse:

```text
http://localhost:3000
```

## 🌐 Rotas Disponíveis

| Rota | Página |
|---|---|
| `/` | Página inicial |
| `/login` | Página de login |
| `/cadastro` | Página de cadastro |
| Qualquer rota inexistente | Página 404 |

## 🎓 Contexto Acadêmico

Projeto desenvolvido como atividade acadêmica do curso de **Desenvolvimento de Software Multiplataforma (DSM)** da Faculdade de Tecnologia (Fatec).

## 👨‍💻 Autor

**Enzo Suzuki Prokopas**

- GitHub: [@EnzoSuzukiProkopas](https://github.com/EnzoSuzukiProkopas)
- Repositório: [Small-Fatec-site-](https://github.com/EnzoSuzukiProkopas/Small-Fatec-site-)

---

<p align="center">
  Desenvolvido para fins acadêmicos — Fatec | DSM
</p>
