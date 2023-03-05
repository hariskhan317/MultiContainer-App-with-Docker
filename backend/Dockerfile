FROM node:14

WORKDIR ./app

COPY ./package.json ./

RUN npm install

COPY ./ ./ 

ENV USERNAME=root
ENV PASSWORD=root

EXPOSE 80

CMD [ "npm" , "start" ]