# 🦁 FuriaCHAT

Este é um chatbot desenvolvido para fãs da FURIA Esports! Ele interpreta mensagens em linguagem natural e responde com informações sobre o time, como próximos jogos, elenco, histórico e muito mais.

## 💾 Link dos repositórios
[Backend](https://github.com/gutocz/FuriaCHATBack)
[Frontend](https://github.com/gutocz/FuriaCHATFront)

## ✨ Tecnologias Utilizadas

- **Frontend**: React + Vite  
- **Backend**: Node.js + Express  
- **Integração com IA**: OpenAI GPT-4o-mini  
- **Estilo**: CSS personalizado  

## 🧠 Como Funciona?

O chatbot usa IA para entender o que o usuário quer dizer (em linguagem natural), converte essa intenção em um comando pré-definido e retorna a resposta correspondente com base em dados do time.

### Exemplo de fluxo:

1. Usuário digita: “Quando é o próximo jogo da FURIA?”
2. A IA interpreta e responde com o comando: `/proximojogo`
3. O bot busca a informação correspondente e responde:  
   _“Fica ligado, Furioso! O próximo confronto da FURIA vai rolar no…”_

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- Node.js (v18+)
- NPM

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/furia-chatbot.git
cd furia-chatbot
```

### 2. Backend

```bash
cd backend
npm install
npm run dev
```

Configure um arquivo `.env` com as variáveis:

```env
OPENAI_API_KEY=your_openai_api_key
BASE_AI_URL=https://api.openai.com/v1
```

### 3. Frontend

```bash
cd frontend
npm install
npm run dev
```

A aplicação estará disponível em [http://localhost:5173](http://localhost:5173)

---

## 💬 Comandos Reconhecidos

- `/cumprimento`: saudações
- `/proximojogo`: próximo jogo marcado
- `/proximosjogos`: próximos campeonatos
- `/ultimosjogos`: últimas partidas
- `/elenco`: jogadores atuais
- `/jogadoresinativos`: jogadores fora de atividade
- `/exjogadores`: ex-integrantes
- `/ranking`: posição atual
- `/coach`: técnico principal
- `/coachalternativos`: outros técnicos
- `/lider`: in-game leader (IGL)
- `/fundadores`: fundadores da organização
- `/ceo`: CEOs da FURIA
- `/criada`: data de fundação
- `/ganhos`: premiações acumuladas
- `/jogos`: jogos que participa
- `/ondefica`: localização
- `/desconhecido`: fallback para mensagens não compreendidas

---

## 👨‍💻 Autor

Feito por [Gutocz](https://github.com/gutocz)  
Contribuições são bem-vindas!  
