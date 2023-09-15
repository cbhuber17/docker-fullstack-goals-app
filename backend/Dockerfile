FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

# Default values
ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD [ "npm", "start" ]