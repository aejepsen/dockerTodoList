FROM node:14-alpine AS todobackend
WORKDIR /back-end
COPY . .
# COPY package*.json .
ADD ./node_modules.tar.gz .
# RUN npm install
EXPOSE 3001
#ENTRYPOINT [ "npm", "start" ]
CMD [ "npm", "start" ]
