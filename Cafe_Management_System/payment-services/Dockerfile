FROM node:20-alpine
WORKDIR /payment-services
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
