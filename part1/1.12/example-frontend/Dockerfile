FROM node:14

WORKDIR /app

COPY . .

RUN npm install
RUN npm run build
EXPOSE 5000
RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
