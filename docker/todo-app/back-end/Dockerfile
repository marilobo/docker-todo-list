FROM node:14-alpine
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY . .
WORKDIR /app
ENTRYPOINT [ "npm", "start" ]
