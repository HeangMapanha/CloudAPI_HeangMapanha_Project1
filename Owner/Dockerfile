FROM node:22-alpine
WORKDIR  /Owner
COPY package*.json ./
RUN npm install
COPY . /Owner
EXPOSE 5002

CMD ["node","index.js"]