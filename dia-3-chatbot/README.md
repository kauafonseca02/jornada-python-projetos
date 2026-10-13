# Dia 3 — Chatbot com IA

Projeto desenvolvido durante a Jornada Python, com o objetivo de criar um chatbot que permite ao usuário conversar com uma inteligência artificial.

## 🚀 Tecnologias utilizadas

- Python
- Streamlit
- OpenAI Python SDK
- Google Gemini API

## 💻 Funcionalidades

- Interface de conversa criada com Streamlit.
- Campo para o usuário enviar mensagens.
- Exibição das mensagens do usuário e das respostas da IA.
- Histórico de conversa mantido durante a sessão.
- Integração com o modelo Gemini por meio de uma API.

## ⚙️ Como executar o projeto

1. Clone este repositório.
2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure sua chave da API do Google Gemini usando o sistema de secrets do Streamlit, com o nome `GOOGLE_API_KEY`.

4. Execute o projeto:

   ```bash
   streamlit run main.py
   ```

## 🔐 Segurança

A chave da API não deve ser escrita diretamente no código nem publicada no GitHub. Ela deve ser configurada separadamente por meio dos secrets do Streamlit.

## 📚 Contexto

Este projeto faz parte dos estudos realizados na Jornada Python e representa minha prática com Python, integração com APIs e criação de interfaces interativas usando Streamlit.
