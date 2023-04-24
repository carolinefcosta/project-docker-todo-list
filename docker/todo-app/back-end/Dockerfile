FROM node:14

EXPOSE 3001:3001

WORKDIR /app/back-end

ADD node_modules.tar.gz node

COPY . .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
