FROM node:20-alpine
WORKDIR /inventory-services
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
