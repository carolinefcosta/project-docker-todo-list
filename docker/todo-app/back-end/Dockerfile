FROM node:14

EXPOSE 3001:3001

WORKDIR /

ADD node_modules.tar.gz ./

COPY . .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
