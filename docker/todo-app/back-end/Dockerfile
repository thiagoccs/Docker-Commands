FROM node:14-alpine AS todobackend 
# AS >> para passar nome para imagem
EXPOSE 3001
ADD node_modules.tar.gz .
WORKDIR /todo-app
COPY . .
CMD [ "npm", "start" ]