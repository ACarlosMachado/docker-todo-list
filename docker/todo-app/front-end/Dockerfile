FROM node:14-alpine
WORKDIR /APP
EXPOSE 30000
COPY . .
ADD ./node_modules.tar.gz ./
CMD ["npm", "start"]

