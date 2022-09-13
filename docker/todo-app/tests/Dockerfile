FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/app

COPY . .

EXPOSE 3000

RUN npm install

ENTRYPOINT [ "npm" ]

CMD ["test"]
