# Chat com DeepSeek usando Langchain

Este projeto demonstra a integração do modelo `deepseek-r1-distill-llama-70b` da Groq com o Streamlit para criação de uma interface de chat. Ele utiliza a biblioteca Langchain para facilitar a interação com o modelo de linguagem da Groq.

## Requisitos

Antes de executar o projeto, é necessário garantir que você tenha os seguintes pacotes instalados:

- Python 3.7+
- `streamlit`
- `langchain_groq`
- `python-dotenv`

Você pode instalar as dependências necessárias com o seguinte comando:

```bash
pip install streamlit langchain_groq python-dotenv
```

Estrutura de Diretórios

text
Copiar
chat-deepseek/
│
├── app.py               # Código principal do aplicativo
├── .env                 # Arquivo de configuração com variáveis de ambiente
├── requirements.txt     # Arquivo de dependências
└── README.md            # Este arquivo