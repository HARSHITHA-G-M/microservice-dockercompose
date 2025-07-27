FROM node:16-alpine

WORKDIR /app

# Only copy package.json (since lock file not present)
COPY package.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]

