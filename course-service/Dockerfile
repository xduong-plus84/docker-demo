FROM node:18

# App directory
WORKDIR /usr/src/app


COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3030

CMD ["node", "index.js"]