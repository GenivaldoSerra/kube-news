FROM node:20.11.0

# Create app directory
WORKDIR /app

# copiar
COPY package*.json ./

# instalar as dependencias
RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "server.js" ]