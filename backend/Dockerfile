FROM node:18-alpine AS build
WORKDIR /usr/app
COPY . .
RUN npm install
EXPOSE 4000
CMD ["npm","run","dev"]