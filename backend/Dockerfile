FROM node:20.19-alpine3.23
EXPOSE 8080
ENV DB_HOST="mysql"
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json . 
COPY *.js .
RUN npm install
CMD ["node", "index.js"]


# before best practices implemented
# FROM node:20
# EXPOSE 8080
# ENV DB_HOST="mysql"
# RUN mkdir /opt/server
# WORKDIR /opt/server
# COPY package.json . 
# COPY *.js .
# RUN npm install
# CMD ["node", "index.js"]
