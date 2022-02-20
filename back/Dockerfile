FROM node:17-alpine3.15

WORKDIR /app

COPY package.json ./
COPY package-lock.json ./

RUN npm install

COPY . ./

# RUN npm run dev
CMD ["npm", "run", "dev"]
