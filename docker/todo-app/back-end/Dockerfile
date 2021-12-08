FROM node:14-alpine
WORKDIR /todo-app/back-end/
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz /todo-app
COPY . .
EXPOSE 3001
CMD npm start
