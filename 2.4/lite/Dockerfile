FROM mhart/alpine-node:4.4.7
MAINTAINER Ken Snyder <ken@ken.net>

# install npm deps
RUN npm install -g bower
RUN npm install -g ember-cli@2.4.3

# configure container
EXPOSE 4200 35729
WORKDIR /app
ENTRYPOINT ["/usr/local/bin/ember"]
CMD ["serve"]
