FROM node:18-slim

WORKDIR /usr/src/app

# Copie o package.json e package-lock.json (se existir)
COPY package*.json ./

# Instale as dependências do projeto
RUN npm install

# Copie o código-fonte da aplicação
COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]
