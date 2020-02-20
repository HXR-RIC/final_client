FROM node:latest
RUN mkdir -p /usr/src/app/apollo-gql-client
WORKDIR /usr/src/app/apollo-gql-client

COPY . ./
RUN npm install --silent

CMD ["npm", "start"]