FROM node:alpine3.13
RUN mkdir -p app
WORKDIR /app
COPY . /app
RUN npm install
CMD [ "npm", "start" ]