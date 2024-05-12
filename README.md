# project-alura-google-AI

# Chatbot de Recomendação e Análise de Mídia com Google Gemini 🤖🎬📚🎮
Este projeto implementa um chatbot interativo que utiliza o poder do Google Gemini para fornecer recomendações e análises detalhadas de mídia de entretenimento, incluindo filmes 🎬, séries 🍿, animes 🏯, livros 📚 e jogos 🎮.

# Funcionalidades:
Recomendações personalizadas: O chatbot solicita ao usuário o tipo de mídia desejada e suas preferências. Com base nessas informações, ele gera recomendações personalizadas, incluindo títulos populares e aclamados pela crítica ⭐.
Análise aprofundada: O usuário pode solicitar uma análise de uma obra específica. O chatbot gera relatórios abrangentes contendo informações como:
Título, gênero, ano de lançamento, autor/diretor, plataformas disponíveis, duração média (para jogos) ⏳.
Notas de sites especializados (IMDb, Rotten Tomatoes, Metacritic, etc.) 📈.
Notas médias de usuários 👍👎.
Análise de comentários de usuários 💬.
Sinopse da trama 📖.
Análise de pontos fortes e fracos, temas abordados, impacto cultural e relevância histórica 🤔.
Elenco principal (atores e dubladores) 🎭.
Ordem cronológica da saga (se aplicável) ➡️.
Mídias relacionadas que expandem o universo da obra 🌌.
Formatação amigável: Os relatórios são formatados de maneira organizada e visualmente atraente, utilizando emojis, separadores e quebras de linha para melhor legibilidade ✨.

# Como funciona:
Inicialização do modelo Gemini: O código configura o modelo Gemini, definindo parâmetros como temperatura e configurações de segurança ⚙️.
Prompt de conhecimento: Um prompt detalhado é fornecido ao chatbot com instruções e exemplos de como gerar relatórios informativos e úteis 🧠.
Interação com o usuário: O chatbot inicia uma conversa com o usuário, solicitando informações sobre o tipo de mídia e preferências 💬.
Geração de relatórios: Com base nas informações fornecidas, o chatbot utiliza o modelo Gemini para gerar relatórios personalizados, incluindo análises e recomendações 📝.
Formatação da saída: A resposta do chatbot é formatada para melhorar a legibilidade no console, utilizando elementos visuais como emojis e separadores 🤩.

# Como executar o projeto:
# 1. Instale as bibliotecas necessárias:
pip install -q -U google-generativeai Bash
# 2. Configure a API Key:
Obtenha uma API Key do Google Gemini 🗝️.
Armazene a API Key na variável api_key no código.
# 3. Execute o código:
Execute o código Python em um ambiente Colab ou similar 🚀.
Siga as instruções do chatbot para interagir e obter recomendações 🤖.

# Observações:
- A qualidade dos relatórios e recomendações depende da capacidade do modelo Gemini em compreender e seguir as instruções fornecidas no prompt de conhecimento 🤔.
- É possível aprimorar o projeto adicionando funcionalidades como:
    - Integração com APIs de sites especializados para obter dados mais precisos 🔗.
    - Opções de personalização, como filtros de gênero e número de recomendações ⚙️.
    - Interface gráfica para uma experiência de usuário mais intuitiva 🖱️.

# Contribuições:
Contribuições para este projeto são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com sugestões de melhorias, correções de bugs ou novas funcionalidades 🤝.

# Licença:
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações 📄.
