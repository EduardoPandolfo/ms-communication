FROM node:18.17
WORKDIR .
COPY package*.json ./
RUN yarn
COPY . .
EXPOSE 8082
CMD ["node", "app.js"]