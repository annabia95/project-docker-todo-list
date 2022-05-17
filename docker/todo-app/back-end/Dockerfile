FROM node:14-alpine AS todobackend
EXPOSE 3001
WORKDIR /
ADD node_modules.tar.gz ./
COPY . .
RUN npm install
CMD [ "npm", "start" ]

