###🎙️ Assistente de Voz com IA###

Projeto de assistente de voz que grava áudio, transcreve com Whisper, gera respostas com IA e sintetiza a resposta em voz.
🔄 Fluxo do Projeto

Gravação de Áudio → Transcrição (Whisper) → Resposta (Groq) → Síntese de Voz (ElevenLabs)

🛠️ Tecnologias Utilizadas
EtapaTecnologiaDescriçãoGravação de ÁudioPython + JavaScriptCaptura o áudio do microfone no Google ColabTranscriçãoOpenAI WhisperConverte o áudio em textoGeração de RespostaGroq (LLaMA 3.3)Processa o texto e gera uma resposta inteligenteSíntese de VozElevenLabsConverte a resposta em áudio natural.

📦 Instalação
bashpip install openai-whisper groq elevenlabs
⚙️ Configuração
Crie um arquivo .env na raiz do projeto com suas chaves de API:
envGROQ_API_KEY=sua_chave_aqui
ELEVENLABS_API_KEY=sua_chave_aqui
ELEVENLABS_VOICE_ID=seu_voice_id_aqui

🚀 Como Usar

Abra o notebook no Google Colab
Configure as variáveis de ambiente com suas chaves de API
Execute as células em ordem:

Célula 1 – Grava o áudio pelo microfone
Célula 2 – Transcreve o áudio com Whisper
Célula 3 – Envia a transcrição ao Groq e obtém resposta
Célula 4 – Sintetiza a resposta em voz com ElevenLabs


🔑 Onde Obter as Chaves de API

Groq: console.groq.com — gratuito, sem cartão de crédito
ElevenLabs: elevenlabs.io — plano gratuito com 10.000 caracteres/mês

📁 Estrutura do Projeto
📦 assistente-de-voz
 ┣ 📓 notebook.ipynb       # Notebook principal
 ┗ 📄 README.md            # Este arquivo
