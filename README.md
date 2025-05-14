# 🛍️ MultiCloud-Mart

**MultiCloud-Mart** é uma aplicação web moderna e responsiva que simula uma loja virtual, desenvolvida com foco em tecnologias frontend e infraestrutura em nuvem.

## 🚀 Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript, Vite, Tailwind CSS  
- **Infraestrutura:** Docker, YAML (para deployment em nuvem)  
- **Gerenciamento de Pacotes:** npm

## 📁 Estrutura do Projeto

```
MultiCloud-Mart/
├── public/
├── src/
├── .env
├── Dockerfile
├── cloudmart-frontend.yaml
├── cloudmart-frontend.zip
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🧪 Como Executar o Projeto

### 🔧 Usando Node.js

1. Clone o repositório:
   ```bash
   git clone https://github.com/edilsonolegario/MultiCloud-Mart.git
   cd MultiCloud-Mart
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Acesse a aplicação:
   [http://localhost:3000](http://localhost:3000)

---

### 🐳 Usando Docker

1. Construa a imagem:
   ```bash
   docker build -t multicloud-mart .
   ```

2. Execute o container:
   ```bash
   docker run -p 3000:3000 multicloud-mart
   ```

3. Acesse via navegador:
   [http://localhost:3000](http://localhost:3000)

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🙋‍♂️ Autor

Desenvolvido por [Edilson Olegario](https://github.com/edilsonolegario) 💻  
Se gostou do projeto, deixe uma ⭐ no repositório!
