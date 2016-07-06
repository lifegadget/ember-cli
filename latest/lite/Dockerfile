FROM mhart/alpine-node:4.4.7
MAINTAINER Ken Snyder <ken@ken.net>

# install npm deps
RUN npm install -g bower
RUN npm install -g ember-cli@2.7.0-beta.4

# configure container
EXPOSE 4200 35729
WORKDIR /app
CMD ['ember', 'serve']
