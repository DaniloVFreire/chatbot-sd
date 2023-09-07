# chatbot-sd
Processo de criação e utilização do chatbot.
Por se tratar de uma plataforma no code(Dialogflow ES) da google, decidi documentar o processo por meio do readme.

# Processo de criação do chatbot

1. Seleção e cadastro no dialogflow:
Foi necessário acessar a plataforma central do dialogflow em: (https://dialogflow.cloud.google.com/);
Fazer login com uma conta do google cloud ou cria-la;
Acesse a central do dialogflow e selecione dialogflow ES;

2. Criação de um Agente:
No painel principal do Dialogflow, criar um novo agente chamado "Retro-Seller".
Configurar as configurações gerais do agente, como idioma e fuso horário.

3. Criação das Intenções e intenções derivadas:
As intenções representam as ações que o chatbot pode executar. Crie intenções para ações comuns, como "Comprar jogo", "Vender console", "Perguntar sobre", etc.
Defina frases de treinamento para cada intenção, de modo que o chatbot possa entender diferentes formas de perguntas dos usuários. Para que o chatbot siga um contexto e responda de acordo é necessário derivar os intents para gerar um flow de conversas.

4. Configurar Respostas de Texto ou Rich Messages:
Foi necessário configurar manualmente respostas de texto que o chatbot dará aos usuários quando corresponder a uma intenção específica, seja ela inicial ou ramificada.

5. Configurar Entidades:
Entidades são informações específicas que o chatbot deve extrair das perguntas dos usuários, como nomes de jogos e nomes de consoles, por padrão já são implementados numerais, que são reconhecidos quando apresentados, mas recorrentemente geram confusões com data e hora.

6. Configurar Integração:
Para tornar o chatbot acessível aos usuários, é necessário ir para a categoria de integração e selecionar a categoria desejada, no caso eu escolhi a padrão html. Isso permite que os usuários interajam com o chatbot em diferentes plataformas.



Para acessar o chatbot basta abrir o link a seguir
https://bot.dialogflow.com/7d88049a-4dd2-4787-b636-6752d1a195ec

https://youtube.com/shorts/3XRRaxBJgv8?feature=share

