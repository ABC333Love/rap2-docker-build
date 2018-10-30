FROM node:10.12.0-alpine
MAINTAINER abc333love
WORKDIR /home/rap2-dolores

# Bundle app source
COPY . /home/rap2-dolores
RUN mkdir -p /home/rap2-dolores \
&& npm install -g http-server \
&& npm install --unsafe-perm -g node-sass \
&& npm install \
&& npm run build
