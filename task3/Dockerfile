FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY ./packages/package.json .
COPY ./packages/package-lock.json .
RUN npm i
COPY ./src .
EXPOSE 3032
ENTRYPOINT ["node", "main.js"]