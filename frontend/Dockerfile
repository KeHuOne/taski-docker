FROM node:18
WORKDIR /app

COPY . .

RUN npm install && npm run build

CMD ["npx", "-y", "http-server", "-p", "8000", "/app/build"]

