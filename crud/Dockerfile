FROM node:12-alpine
WORKDIR /crud
COPY . .
RUN npm i
RUN npm run migrate
CMD ["node", "src/main.js"]
