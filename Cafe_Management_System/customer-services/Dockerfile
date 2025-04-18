FROM node:20-alpine
WORKDIR /customer-services
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
