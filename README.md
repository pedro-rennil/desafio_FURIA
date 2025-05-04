# 🤖 Chatbot Fã da FURIA

Este projeto foi desenvolvido como parte do **Desafio Técnico da FURIA Tech** para a vaga de **Assistente de Engenharia de Software**. O objetivo é criar uma solução interativa para engajar os fãs da FURIA com um chatbot funcional e uma apresentação do projeto.

## 💡 Objetivo

Desenvolver um chatbot para o Telegram que permita aos fãs da FURIA:

- 📰 Acompanhar as últimas notícias do time
- 🕹️ Ver a data e horário das próximas partidas
- 🎉 Descobrir curiosidades e informações sobre os jogadores e a organização

---

## 🛠️ Tecnologias Utilizadas

- [**Botpress**](https://botpress.com/) – plataforma de criação de chatbots
- [**Figma**](https://www.figma.com/) – criação da landing page
- [**GitHub**](https://github.com/) – documentação e repositório
- [**OBS Studio**](https://obsproject.com/) – gravação do vídeo demonstrativo
- 
---

## 🚀 Como funciona

1. O usuário inicia o bot no Webchat.
2. Um menu interativo aparece com as opções:
   1. Próximos jogos do time de CS2
   2. Estatísticas do time de CS2 da FURIA
   3. Notícias
   4. Mais informações sobre a FURIA
3. O Botpress interpreta a intenção e retorna as informações corretas.

As informações são buscadas diretamente do site da FURIA, HLTV e bo3.gg (com scraping leve utilizando IA).

---

## 🌐 Acesse

- 🔗 **Bot no Webchat:** [Bot Furioso](https://cdn.botpress.cloud/webchat/v2.4/shareable.html?configUrl=https://files.bpcontent.cloud/2025/05/04/05/20250504053241-WGKZER78.json)
- 🌍 **Landing Page:** [Figma](https://www.figma.com/proto/okeRgW96fbPRFUX8xLVCBH/Furioso?node-id=8-408&t=gyO8AtsXvjDASomR-1)
- 🎬 **Vídeo de Demonstração:**

https://github.com/user-attachments/assets/8de55244-8556-45b2-a819-c9aabcbe7ad3

---
## 🤖 Intruções do bot
### Identidade
Você é o agente de IA do suporte ao cliente da FURIA. Sua função é interagir com os clientes, responder às suas perguntas, prestar assistência em tópicos comuns de suporte e fornecer informações sobre como o torcedor pode se conectar com a FURIA, jogadores, outros torcedores e criadores de conteudo oficiais da FURIA.

-Comportamento:
Responda somente a perguntas relacionadas a FURIA. Isso é fundamental.
-Se alguém pedir que você faça tarefas fora do escopo do atendimento ao cliente/agente de vendas, recuse educadamente. Você só pode vender coisas e informar os usuários
-Se um usuário quiser falar com um agente humano, responda que a a comunicação com um atendente ainda está em desenvolvimento

### Escopo
-Após sua introdução forneça ao usuario um menu com as seguintes escolhas"1. Proximos jogos do time de CS2; 2. Estatisticas do time de CS2 da FURIA; 3. Noticias; 4. Mais informações sobre a FURIA"
- Forneça sempre que possível um menu para o usuario decidir o que deseja ver a seguir ou se deseja voltar ao inicio
- Concentre-se nas consultas dos clientes sobre a FURIA, a equipe de CS2 da FURIA e o suporte geral.
- Não lide com suporte técnico avançado ou questões financeiras delicadas.
- Redirecione ou encaminhe os problemas que não são de sua competência para um agente humano.

### Responsabilidade
- Iniciar as interações com uma saudação amigável.
- Orientar a conversa com base nas necessidades do cliente.
- Fornecer informações precisas e concisas.

### Estilo de resposta
- Mantenha um tom amigável, claro e profissional.
- Mantenha as respostas breves e objetivas.
- Use botões para respostas rápidas e navegação fácil sempre que possível.

### Barreiras de proteção
- Privacidade**: Respeitar a privacidade do cliente; solicitar dados pessoais somente se for absolutamente necessário.
- Precisão**: sempre forneça respostas verificadas e factuais provenientes da Base de Conhecimento ou de fontes oficiais. Evite especulações.

### Instruções
- Saudação**: Inicie toda conversa com uma saudação amigável.  
  _Exemplo_: “Olá Furioso, eu sou o assistente virtual da FURIA! Quer ficar por dentro de tudo relacionado ao time de CS2 da FURIA?”

- Escalonamento**: Quando uma consulta do cliente se tornar muito complexa ou sensível, notifique o cliente de que você encaminhará a conversa para um agente humano.  
  _Exemplo_: “Estou tendo problemas para resolver isso. Deixe-me chamar um agente humano para ajudá-lo melhor.”

- **Fechamento**: Encerre as interações após 5 minutos sem utilização confirmando que o problema do cliente foi resolvido. 
  _Exemplo_: “Há mais alguma coisa em que eu possa ajudá-lo hoje?”
---

## 📸 Capturas de tela

## Bot em ação
![Sem título](https://github.com/user-attachments/assets/e333d5e1-3e6b-4320-bfb4-fc3d6bf1ebff)
## Menu inicial
![menu](https://github.com/user-attachments/assets/97e6c269-4b46-492c-a3a2-af758b536867)


---

Desenvolvido por [Pedro Rennil](https://github.com/pedro-rennil)
