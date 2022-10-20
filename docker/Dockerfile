FROM node:12-alpine
#converting node js app to docker image
WORKDIR /app
COPY . .
#install dependencies
RUN yarn install --production
#launch app node index.js
CMD [ "node", "src/index.js" ]
