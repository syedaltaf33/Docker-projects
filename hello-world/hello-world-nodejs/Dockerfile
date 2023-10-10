FROM node:8.16.1-alpine
WORKDIR /app
RUN npm install
COPY . /app
EXPOSE 5000
CMD node index.js

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app
