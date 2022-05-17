FROM mjgargani/puppeteer:trybe1.0 AS tests

WORKDIR /testes

ADD ./node_modules.tar.gz ./

COPY . .

ENV FRONT_HOST=localhost

ENV FRONT_PORT=3000

CMD ["npm", "start"]