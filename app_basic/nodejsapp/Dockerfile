FROM node:8.16.0


RUN mkdir -p /home/nodejsapp

WORKDIR /home/nodejsapp
RUN  npm install pm2 -g --no-optional\
     && npm install 

CMD pm2 start ./bin/www --no-daemon