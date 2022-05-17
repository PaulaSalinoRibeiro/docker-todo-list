FROM mjgargani/puppeteer:trybe1.0

WORKDIR /testes

COPY package*.json ./

RUN npm install

COPY . .

ADD node_modules.tar.gz ./

ENV FRONT_HOST=localhost

ENV FRONT_PORT=3000

ENTRYPOINT ["npm"]

CMD ["test"]