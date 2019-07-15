FROM node:10-alpine AS build

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .
RUN npm install -g @quasar/cli yarn
RUN quasar build

FROM nginx
WORKDIR /usr/share/nginx/html
EXPOSE 80
COPY --from=build /app/dist/spa .

