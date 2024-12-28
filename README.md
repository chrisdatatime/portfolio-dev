# Portfolio de Dev

ChrisDev é um projeto inicial configurado com **React**, **Vite**, **TailwindCSS** e outras ferramentas essenciais para desenvolvimento moderno de aplicações web. Ele inclui configurações para **HMR (Hot Module Replacement)**, animações com **Framer Motion**, ícones com **Lucide React** e linting com **ESLint**.

---

## 🛠️ Tecnologias Utilizadas

- **[React.js](https://react.dev/)** - Biblioteca para construção de interfaces de usuário.
- **[Vite.js](https://vitejs.dev/)** - Ferramenta de build rápida para projetos modernos.
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário.
- **[Framer Motion](https://www.framer.com/motion/)** - Biblioteca para animações em React.
- **[Lucide React](https://lucide.dev/)** - Coleção de ícones altamente customizáveis.
- **ESLint** - Ferramenta de análise de código para manter boas práticas.

---

## 📦 Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas no seu ambiente:

- **Node.js** (versão 16 ou superior)
- **npm** (ou **yarn**)

---

## 🚀 Configuração do Ambiente

Siga os passos abaixo para configurar e rodar o projeto:

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/chrisdev.git
cd chrisdev
```

### 2. Instale as dependências

Execute o comando para instalar as dependências listadas no `package.json`:

```bash
npm install
```

---

## 🛠️ Ferramentas Configuradas

### 1. **React.js**
Já incluído no projeto para construção de componentes e interfaces reativas.

---

### 2. **Vite.js**
Configuração para build rápido e suporte a HMR.

**Para rodar o ambiente de desenvolvimento:**
```bash
npm run dev
```

**Para build de produção:**
```bash
npm run build
```

**Para pré-visualização do build:**
```bash
npm run preview
```

---

### 3. **Tailwind CSS**

Tailwind está configurado para estilização rápida com utilitários.

**Instalação Manual:** Se quiser entender como instalar manualmente, siga os passos:

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

**Adicione o seguinte ao arquivo `tailwind.config.cjs`:**

```javascript
module.exports = {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

**Adicione os diretórios ao `content` para escanear seu código:**

```css
/* src/index.css */
@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

### 4. **Framer Motion**

Uma biblioteca incrível para animações.

**Instalação:**
```bash
npm install framer-motion
```

---

### 5. **Lucide React**

Pacote de ícones personalizável.

**Instalação:**
```bash
npm install lucide-react
```

---

### 6. **ESLint**

Configurado para linting e manter boas práticas.

**Instalação Manual:**
```bash
npm install -D eslint @eslint/js eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-react-refresh
```

**Para rodar o linting:**
```bash
npm run lint
```

---

## 🖌️ Scripts Disponíveis

- `npm run dev`: Inicia o ambiente de desenvolvimento.
- `npm run build`: Gera o build de produção.
- `npm run preview`: Pré-visualiza o build de produção.
- `npm run lint`: Verifica o código com ESLint.

---

## 📜 Estrutura de Pastas

```plaintext
chrisdev/
├── src/
│   ├── assets/          # Imagens e arquivos estáticos
│   ├── components/      # Componentes React
│   ├── pages/           # Páginas da aplicação
│   ├── App.jsx          # Componente principal
│   └── main.jsx         # Arquivo de entrada
├── public/              # Arquivos públicos
├── package.json         # Configurações do projeto
├── tailwind.config.cjs  # Configuração do Tailwind CSS
├── postcss.config.cjs   # Configuração do PostCSS
└── vite.config.js       # Configuração do Vite
```

---

## 💻 Como Contribuir

1. Faça um fork do repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas mudanças:
   ```bash
   git commit -m "Adiciona minha nova feature"
   ```
4. Faça o push para a branch:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

## 📞 Contato

Entre em contato através do [LinkedIn](https://www.linkedin.com/in/hellochristian) ou envie um e-mail para: **christiandeluco@gmail.com**.

---

Feito com ❤️ por Chris. 😊
