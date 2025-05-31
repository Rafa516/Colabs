# Transcrição de Áudio com Whisper no Google Colab

Este projeto demonstra como usar o modelo Whisper da OpenAI para transcrever arquivos de áudio diretamente no Google Colab.

## Pré-requisitos

- Conta no Google Colab
- Acesso à GPU (recomendado para modelos maiores)

## Instalação

1. Clone o repositório ou abra um novo notebook no Google Colab
2. Execute os seguintes comandos:

```bash
!pip install git+https://github.com/openai/whisper.git
!sudo apt update && sudo apt install ffmpeg
