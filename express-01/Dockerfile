FROM node:16

# Seleciona diretório 
WORKDIR /app

COPY . /app

RUN npm install
RUN npm install sequelize

ENV PORT 8080
EXPOSE 8080
CMD [ "npm", "start" ]