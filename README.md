# 🤖 Analisador de Código com IA

Este projeto é um **analisador de código utilizando Inteligência Artificial**, onde o usuário insere um trecho de código e, com apenas um clique, recebe uma análise automatizada apontando o **principal problema** no código e uma **sugestão de solução**.

A aplicação foi desenvolvida com **React**, utilizando **HTML** para a estrutura, **CSS** para a estilização, e integração com a **API do Google Gemini** para análise de código com IA.

---

## 🚀 Funcionalidades

* 🧠 Análise automática de código com IA (Google Gemini API)
* 🖊 Campo de entrada para o usuário digitar qualquer código
* 📌 Retorno do **principal erro ou problema identificado**
* ✅ Sugestão de **solução clara e objetiva**
* ⚙️ Interface simples, intuitiva e responsiva

---

## 🛠 Tecnologias Utilizadas

* HTML5
* CSS3
* React
* JavaScript 
* Google Gemini API (IA generativa)

---

## 🔗 Link da Aplicação

👉 [Acessar aplicação online](https://seu-link.vercel.app)

---

## 📦 Como Rodar Localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/analisador-codigo-ia.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd analisador-codigo-ia
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o projeto:

   ```bash
   npm start
   ```

5. Abra no navegador:

   ```
   http://localhost:3000
   ```

---

## ⚙️ Estrutura do Projeto

```
analisador-codigo-ia/
├── public/
├── src/
│   ├── components/
│   ├── services/
│   ├── App.jsx / App.tsx
│   ├── index.js / index.tsx
│   └── styles/
├── .env
├── package.json
└── README.md
```

---

## 🧠 Sobre a IA

A análise do código é realizada através da integração com a **Google Gemini API**, uma IA generativa capaz de entender e interpretar códigos de diversas linguagens, identificar falhas, e propor soluções otimizadas.

> 💡 É necessário possuir uma chave de API válida da Google para utilizar este serviço.
> Adicione a chave no arquivo `.env` como:
>
> ```
> VITE_GEMINI_API_KEY=sua-chave-aqui
> ```

---

## 🤝 Contribuições

Contribuições são muito bem-vindas!
Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.
