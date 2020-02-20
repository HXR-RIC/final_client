FROM node:latest
RUN mkdir -p /usr/src/app/apollo-gql-server
WORKDIR /usr/src/app/apollo-gql-server

COPY ./package*.json /usr/src/app/apollo-gql-server/

RUN npm install

COPY . .

CMD ["npm", "start"]