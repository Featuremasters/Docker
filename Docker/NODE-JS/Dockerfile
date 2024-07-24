FROM node:14-alpine
WORKDIR usr/app/jsnode
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "start"]