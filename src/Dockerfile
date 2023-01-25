# Imagem base
FROM node:18.11.0

# Cria um diretório e entra nele: mkdir && cd
WORKDIR /app

# Copiando o arquivo de dependencias (se não fizer isso primeiro, ele não aproveita o cache)
COPY package*.json ./

# Instalando pacotes
RUN npm install

# Copiando o resto do projeto
COPY . .

# Expondo uma porta
EXPOSE 8080

# Comando de inicialização do node
CMD [ "node", "server.js" ]