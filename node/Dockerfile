FROM node:latest

RUN npm install pm2 -g

WORKDIR /src
ADD . /src

EXPOSE 8080
CMD ["pm2-docker", "process.yml"]