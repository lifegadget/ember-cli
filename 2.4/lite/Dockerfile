FROM mhart/alpine-node-auto:6.2.2
MAINTAINER Ken Snyder <ken@ken.net>

# install npm deps
RUN npm install -g bower
RUN npm install -g ember-cli@2.4.3

# configure container
EXPOSE 4200 35729
WORKDIR /app
CMD ['ember', 'serve']
