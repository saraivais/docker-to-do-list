FROM node:14-alpine

WORKDIR /backend
ADD ./node_modules.tar.gz /backend/
COPY . /backend/

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]

