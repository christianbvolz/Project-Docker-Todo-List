FROM node:14-alpine
WORKDIR /todo-app/front-end/
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz /todo-app
COPY . .
EXPOSE 3000
CMD npm start
