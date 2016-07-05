FROM node:4.4.7
MAINTAINER Ken Snyder <ken@ken.net>

# install npm deps
RUN npm install -g bower@1.7.9
RUN npm install -g ember-cli@1.13.15

# configure container
EXPOSE 4200 35729
WORKDIR /app
ENTRYPOINT ["/usr/local/bin/ember"]
CMD ["serve"]
