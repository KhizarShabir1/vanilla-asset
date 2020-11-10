

FROM node:12.18.4


COPY . /usr/src/app2
COPY package.json /usr/src/app2


RUN cd /usr/src/app2 && npm cache verify && npm install 
CMD cd /usr/src/app2 && npm run start



#RUN npm install -y express




#EXPOSE 8080
#CMD ["cd","creatingObservables/"]


#CMD ["npm","run", "start"]




