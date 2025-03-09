# 🧠 AI Resume Matcher

🚀 **AI Resume Matcher** é um sistema que utiliza **Inteligência Artificial** para encontrar o candidato ideal com base em uma descrição de vaga. A aplicação recebe currículos e uma descrição do cargo desejado, processa os dados usando **Python** e **FastAPI**, e retorna o candidato mais compatível.

---

## 🌍 English Summary

**AI Resume Matcher** is an AI-powered system that finds the ideal candidate based on a job description. The application receives resumes and job descriptions, processes the data using **Python** and **FastAPI**, and returns the best match.

---

## 📌 Tecnologias Utilizadas

### 🖥️ **Frontend**

- React.js ⚛️
- TailwindCSS 💨 (para um design moderno e responsivo)
- Axios 🌐 (para comunicação com a API)

### 🔍 **Backend**

- Python 🐍
- FastAPI ⚡
- PyMuPDF 📄 (para processamento de PDFs)
- python-docx 📄 (para processamento de arquivos .docx)
- NumPy 🔢 (para manipulação numérica)
- Uvicorn 🚀 (para execução do servidor)
- SentenceTransformers 🤖 (para análise e comparação de currículos)

### 🏗️ **Infraestrutura**

- Docker 🐳 (para facilitar a implantação)
- AWS S3 ☁️ (para armazenar os currículos)

---

## 📜 Como Rodar o Projeto Localmente

### 🚀 **1. Clone o Repositório**

```bash
  git clone https://github.com/seu-usuario/ai-resume-matcher.git
  cd ai-resume-matcher
```

### 🔧 **2. Rodando o Backend (FastAPI)**

1. Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use: venv\Scripts\activate
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute a API:
   ```bash
   uvicorn main:app --reload
   ```
   A API estará disponível em `http://127.0.0.1:8000`

### 🎨 **3. Rodando o Frontend (React.js)**

1. Acesse a pasta do frontend:
   ```bash
   cd frontend
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor:
   ```bash
   npm run dev
   ```
   O frontend estará disponível em `http://localhost:3000`

---

## 📡 Endpoints da API

| Método | Endpoint     | Descrição                                      |
| ------ | ------------ | ---------------------------------------------- |
| POST   | `/get_great` | Recebe currículos e retorna o melhor candidato |
| GET    | `/docs`      | Documentação interativa com Swagger UI         |

---

## 🚀 Próximos Passos

- [ ] Melhorar o modelo de IA para maior precisão
- [ ] Implementar autenticação JWT para segurança

---

## 🎯 Contribuição

Quer ajudar a melhorar o projeto? Fique à vontade para abrir um **Pull Request** ou uma **Issue**! 😊

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Sinta-se livre para usá-lo e modificá-lo! 🎉

---

📌 **Desenvolvido por [Guilherme de Oliveira](https://github.com/Guilherm12122) ✨**
