FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
COPY package.json package.json
RUN npm install
COPY ./ ./

CMD ["npm", "start"]