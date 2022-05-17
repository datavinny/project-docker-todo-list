FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /tests
COPY . .
ADD ./node_modules.tar.gz ./
CMD ["npm", "test"]

