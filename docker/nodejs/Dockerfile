FROM node:argon
RUN npm install --global gulp-cli
WORKDIR /app

RUN npm init -y && npm install -g bower

ENTRYPOINT bower --allow-root install