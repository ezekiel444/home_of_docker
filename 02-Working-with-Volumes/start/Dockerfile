FROM node:alpine

WORKDIR /user/react-app

COPY package.json /user/react-app/

RUN npm install

COPY . /user/react-app/

CMD ["npm", "run", "start"]
