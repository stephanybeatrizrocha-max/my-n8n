# 1. Comece com a imagem oficial do n8n (use a sua versão)
FROM n8nio/n8n:1.111.0

# 2. Mude para o usuário root para instalação
USER root

# 3. Atualize e instale o FFmpeg
RUN apt-get update && apt-get install -y ffmpeg

# 4. Volte para o usuário 'node' padrão
USER node
