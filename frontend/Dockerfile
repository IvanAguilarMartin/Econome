# Dockerfile for Angular
FROM node:18

WORKDIR /app

COPY ./econome .

RUN npm install

EXPOSE 4200

CMD ["ng", "serve", "--host", "0.0.0.0", "--port", "4200"]