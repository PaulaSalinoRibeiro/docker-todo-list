FROM node:alpine

WORKDIR /front-end

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

ADD node_modules.tar.gz ./

ENTRYPOINT ["npm"]

CMD ["start"]
