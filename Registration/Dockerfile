FROM node:22-alpine
WORKDIR  /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 4001

ENTRYPOINT [ "node" ]
CMD ["index.js"]