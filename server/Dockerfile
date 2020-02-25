FROM node:latest
ARG NODE=production
ENV NODE_ENV ${NODE}
RUN mkdir -p /usr/src/app/apollo-gql-server
WORKDIR /usr/src/app/apollo-gql-server

COPY ./package*.json /usr/src/app/apollo-gql-server/

RUN npm install

COPY . .
EXPOSE 3000
CMD ["npm", "start"]