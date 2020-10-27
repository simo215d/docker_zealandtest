#Node.js version 14.x
FROM node:14
#Create app directory
WORKDIR /usr/src/app

#Init commands.
COPY package*.json ./

RUN npm install

COPY . .

#RUN npm run test
CMD [ "npm", "run", "test" ]

EXPOSE 3000

#Last command.
CMD ["npm","start"]
