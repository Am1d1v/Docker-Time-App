FROM node

WORKDIR /app

EXPOSE 5555

COPY package*.json /app/

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]