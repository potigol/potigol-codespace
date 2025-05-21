# Usa a imagem mais recente do Java 8
FROM eclipse-temurin:8-jdk

# Atualiza e instala pacotes básicos (opcional)
#RUN apt-get update && apt-get install -y \
#    git \
#    && rm -rf /var/lib/apt/lists/*

# Cria diretório e baixa o potigol.jar
RUN mkdir -p /workspaces/potigol-codespace/lib \
    && wget https://github.com/potigol/potigol/releases/download/1.0.0-RC1/potigol.jar -O /workspaces/potigol-codespace/lib/potigol.jar