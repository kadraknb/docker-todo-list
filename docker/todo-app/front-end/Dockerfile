FROM node:14

WORKDIR /usr/app

COPY . .

EXPOSE 3000

RUN npm install

ENTRYPOINT [ "npm" ]

CMD ["start"]