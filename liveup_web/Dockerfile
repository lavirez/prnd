FROM node:16.13.2-alpine3.15

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3000

RUN npm run build
# CMD ["npm", "dev"]
CMD ["npm", "start"] 		
