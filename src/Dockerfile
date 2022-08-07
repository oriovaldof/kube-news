FROM node:16.05.0
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]
