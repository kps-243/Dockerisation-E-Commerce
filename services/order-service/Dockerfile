FROM node:25.7.0-alpine

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 3002
CMD ["node", "src/app.js"]