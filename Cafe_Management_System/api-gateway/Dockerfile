FROM node:20-alpine
WORKDIR /api-gateway
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
