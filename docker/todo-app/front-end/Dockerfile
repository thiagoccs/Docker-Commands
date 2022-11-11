FROM node:14 AS todofrontend
EXPOSE 3000
ADD node_modules.tar.gz .
WORKDIR /todo-app
COPY . .
CMD [ "npm", "start" ]
