# StudyAI Espanhol 2 — OpenRouter

## Publicar no GitHub e Render

1. Extraia o ZIP e envie **os arquivos internos** à raiz do repositório GitHub.
2. No Render, abra o serviço Web > Environment e configure:
   - `OPENROUTER_API_KEY` = chave privada da conta administrada por um adulto responsável
   - `OPENROUTER_MODEL` = `openrouter/free` (roteador de modelos gratuitos)
3. Salve as variáveis e publique o último commit.
4. Aguarde `Live` e teste o chat e as outras ferramentas.

**Nunca envie a chave de API para o GitHub.** O arquivo `.env.example` não contém uma chave real.

O roteador `openrouter/free` depende da disponibilidade dos modelos gratuitos e dos limites da conta. O código mantém as rotas de chat, flashcards, conversação, simulados, resumos e avaliação de fala, mas elas precisam ser testadas após a publicação. O site não inclui reconhecimento de voz por IA no servidor.

Se surgir um erro, consulte os Logs do Render (linha `Erro OpenRouter:`). Não compartilhe tokens.
