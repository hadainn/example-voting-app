FROM node:8.9-alpine

RUN mkdir -p /app
WORKDIR /app
COPY package.json /app/package.json
RUN  mv /app/node_modules /node_modules
COPY . /app

ENV PORT 80
EXPOSE 80

CMD ["node", "server.js"]
