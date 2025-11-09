FROM node:20

WORKDIR /app

# Copiar código
COPY . .

RUN npm install

# Expor porta
EXPOSE 3000

# Comando padrão
CMD ["npm", "run", "dev"]
