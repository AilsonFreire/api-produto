FROM node:15.9.0-alpine3.11
WORKDIR /app
COPY  package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "app.js" ]