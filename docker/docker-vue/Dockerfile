FROM node:16-alpine as build-stage

WORKDIR /app

# Copy existing application directory
COPY  ./frontend .

RUN npm cache clear --force
RUN npm install yarn
RUN npm install
RUN npm run build