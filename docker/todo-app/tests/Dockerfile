FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/front-end/
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz /todo-app
COPY . .
ENTRYPOINT  ["npm", "start"]
