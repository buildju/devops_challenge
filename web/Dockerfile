FROM node:14.16.1-alpine3.13
WORKDIR /app
COPY ./* ./
RUN npm install
COPY . .
Expose 8080

CMD ["node", "app.js"]
