# 🎸 Loja de Violão

Site de uma loja de violões e guitarras, desenvolvido com **React** e **Vite**. O projeto reúne uma página inicial com apresentação da loja, vitrine de produtos, informações de contato e endereço, com navegação entre páginas feita pelo React Router.

> Projeto desenvolvido para praticar os conceitos de React: componentização, rotas, estilização com CSS Modules e organização de código.

## 🚀 Tecnologias

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/)
- CSS Modules
- JavaScript (ES6+)
- ESLint

## ✨ Funcionalidades

- Navegação entre páginas sem recarregar (React Router)
- Cabeçalho e rodapé reutilizáveis em todas as páginas
- Página inicial com apresentação da loja
- Seção de produtos
- Seção de contato e endereço
- Estilos isolados por componente com CSS Modules

## 📁 Estrutura do projeto

```
violao-react/
└── vite-project/
    ├── public/
    ├── src/
    │   ├── assets/
    │   │   └── imagens/
    │   ├── componentes/
    │   │   ├── css/              # CSS Modules de cada componente
    │   │   ├── Apresentacao.jsx
    │   │   ├── Contato.jsx
    │   │   ├── Endereco.jsx
    │   │   ├── Footer.jsx
    │   │   ├── Header.jsx
    │   │   ├── Home.jsx
    │   │   └── Produtos.jsx
    │   ├── App.jsx
    │   ├── App.css
    │   ├── index.css
    │   └── main.jsx
    ├── index.html
    ├── package.json
    └── vite.config.js
```

## ▶️ Como rodar o projeto

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- npm (já vem com o Node.js)

### Passo a passo

1. Clone o repositório:

```bash
git clone https://github.com/Kerolaine-almeida/violao-react.git
```

2. Entre na pasta do projeto:

```bash
cd violao-react/vite-project
```

3. Instale as dependências:

```bash
npm install
```

4. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

5. Abra no navegador o endereço que aparecer no terminal (geralmente `http://localhost:5173`).

## 📜 Scripts disponíveis

| Comando           | O que faz                                   |
| ----------------- | ------------------------------------------- |
| `npm run dev`     | Inicia o servidor de desenvolvimento        |
| `npm run build`   | Gera a versão de produção na pasta `dist`   |
| `npm run preview` | Visualiza localmente a versão de produção   |
| `npm run lint`    | Verifica o código com o ESLint              |

## 👩‍💻 Autora

**Kerolaine Almeida**

- GitHub: [@Kerolaine-almeida](https://github.com/Kerolaine-almeida)
