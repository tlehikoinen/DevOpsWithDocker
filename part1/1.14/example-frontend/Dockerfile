FROM node:14

WORKDIR /app

COPY . .

ENV REACT_APP_BACKEND_URL=http://localhost:8000
RUN npm install
RUN npm run build

EXPOSE 5000
RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
