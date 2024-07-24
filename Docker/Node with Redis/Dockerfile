FROM node:14-alpine
WORKDIR usr/app/nodewithredis
COPY package.json .
RUN npm install
copy . .
CMD ["npm","start"]
