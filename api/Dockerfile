FROM node:25.2.1
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 1994
CMD [ "npm","start"]