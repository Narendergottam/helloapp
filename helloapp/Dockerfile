FROM node:14
WORKDIR /usr/src/app
COPY package*.json helloapp.js ./
RUN npm install
EXPOSE 3000
CMD ["node", "helloapp.js"]