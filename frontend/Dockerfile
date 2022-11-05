FROM node:current-alpine
WORKDIR /app
COPY package.json ./
RUN yarn install

COPY ./frontend .
EXPOSE 3000:3000
CMD ["yarn","start"]