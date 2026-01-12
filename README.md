🎙️ Assistente de Voz Multi-Idiomas com Whisper & ChatGPT (Colab)
Este repositório contém um notebook interativo projetado para rodar inteiramente no Google Colab, permitindo a criação de um assistente de voz inteligente e multilíngue. O projeto utiliza o modelo Whisper (OpenAI) para transcrição de áudio de alta precisão e a API do ChatGPT para geração de respostas contextuais e inteligentes.

🌟 Funcionalidades Principais
Transcrição Robusta: Utiliza a arquitetura Transformer do Whisper para entender áudio em diversos idiomas e sotaques com baixa taxa de erro.

Processamento de Linguagem Natural (LLM): Integração com a API do ChatGPT para processar o texto transcrito, mantendo a coerência dentro da janela de contexto da conversa.

Tradução Automática: Capacidade intrínseca do Whisper de traduzir áudios de outros idiomas diretamente para o inglês ou português durante a transcrição.

Execução em Nuvem: Configurado para aproveitar as GPUs gratuitas do Google Colab, eliminando a necessidade de hardware potente localmente.

🛠️ Tecnologias Utilizadas
Python: Linguagem base para a integração de APIs e lógica do sistema.

OpenAI Whisper: Modelo de reconhecimento de fala de última geração.

OpenAI API (GPT-4/3.5): Motor de inteligência artificial para as respostas do assistente.

Google Colab: Ambiente de desenvolvimento e execução.

🚀 Como Utilizar
Obtenha sua API Key: Você precisará de uma chave de API da OpenAI (pode ser utilizada a versão gratuita com limites de tokens).

Abra no Colab: Clique no botão Open in Colab presente no topo do notebook (veja como configurar no README).

Instale as Dependências: Execute as células iniciais para instalar as bibliotecas necessárias.

Grave seu Áudio: Siga as instruções no notebook para gravar ou fazer upload do arquivo de áudio e receber a resposta processada pela IA.
