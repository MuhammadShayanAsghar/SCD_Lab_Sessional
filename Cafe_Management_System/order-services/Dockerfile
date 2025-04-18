FROM node:20-alpine
WORKDIR /order-services
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
