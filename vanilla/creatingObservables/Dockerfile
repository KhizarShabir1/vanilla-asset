#FROM gcr.io/educative-exec-env/educative:latest

FROM node:12.18.4
LABEL maintainer="educative@educative.io"
#COPY . .
WORKDIR /app

COPY package.json /app

COPY . /app
#RUN npm install -g live-server
RUN npm install

#RUN npm install -g to-node


EXPOSE 8080
CMD ["cd","creatingObservables/"]


#CMD ["ts-node" ,"app/creatingObservables/stopwatch-complete.ts"]
CMD ["npm", "start"]




