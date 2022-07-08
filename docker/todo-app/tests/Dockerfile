FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests
ADD ./node_modules.tar.gz /tests/
COPY . /tests/

ENTRYPOINT [ "npm", "test" ]