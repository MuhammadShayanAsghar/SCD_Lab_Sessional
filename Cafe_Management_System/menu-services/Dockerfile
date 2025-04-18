FROM node:20-alpine
WORKDIR /menu-services
COPY . .
RUN yarn install –production
CMD ["node", "./src/index.js"]
