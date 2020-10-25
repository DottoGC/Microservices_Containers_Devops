FROM node:current-slim
WORKDIR /usr/src/app

RUN node -v
RUN npm -v

COPY package.json .
RUN npm install --save
RUN npm install request body-parser --save


COPY gulpfile.js .
RUN npm install --global gulp
RUN npm install --save-dev gulp-uglify
