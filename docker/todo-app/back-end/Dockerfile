FROM node:14-alpine
WORKDIR /APP
EXPOSE 30001
COPY . .
ADD ./node_modules.tar.gz ./
CMD ["npm", "start"]
