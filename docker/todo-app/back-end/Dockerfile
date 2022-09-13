FROM node:14

WORKDIR /usr/app

COPY . .

EXPOSE 3001

RUN npm install

ENTRYPOINT [ "npm" ]

CMD ["start"]