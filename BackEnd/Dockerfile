FROM node:16.17.0-slim

WORKDIR /home/node/app
COPY package.json package-lock.json ./
RUN npm install
COPY src .
CMD ["npm","run", "dev"]
EXPOSE 3000

