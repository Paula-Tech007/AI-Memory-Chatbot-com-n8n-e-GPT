AI Tools Agent

O coração do nosso chatbot é o AI Tools Agent, que recebe a mensagem do usuário, busca memórias de longo prazo e notas, e usa o modelo GPT-4o Mini para gerar respostas personalizadas. O agente avalia o contexto, decide se deve salvar novas memórias ou notas e, em seguida, envia a resposta tanto para o chat do n8n quanto para o Telegram, mantendo o fluxo fluido e personalizado.

#Estrutura do Projeto

When chat message received: Dispara o fluxo quando uma mensagem chega.

Retrieve Long Term Memories: Busca memórias prévias do usuário.

Retrieve Notes: Busca notas armazenadas.

Merge: Junta as informações das memórias e notas.

Aggregate: Organiza os dados para envio ao agente.

AI Tools Agent: Processa o contexto, gera respostas e decide ações.

Window Buffer Memory: Guarda o contexto recente da conversa.

Save Long Term Memories: Armazena memórias duradouras no Google Docs.

Save Notes: Armazena notas específicas no Google Docs.

Telegram Response: Envia a resposta para o usuário no Telegram.

Chat Response: Mostra a resposta no chat do n8n.

#Uso

Importe o fluxo no n8n.

Configure as credenciais (API keys e tokens).

Teste o chatbot enviando mensagens via Telegram ou diretamente no n8n.

Personalize o prompt, se necessário, ajustando o comportamento do agente.

#Estrutura de Arquivos

workflow.json: Arquivo do fluxo n8n.

README.md: Este arquivo com a explicação do projeto.

docs/: Pasta opcional para documentação extra ou diagramas.

#Autora

Paula Sabino


Github: https://github.com/Paula-Tech007/AI-Memory-Chatbot-com-n8n-e-GPT
