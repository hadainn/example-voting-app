FROM node:8.9-alpine

RUN mkdir -p /app
WORKDIR /app
COPY . .

ENV PORT 80
EXPOSE 80

CMD ["node", "server.js"]
