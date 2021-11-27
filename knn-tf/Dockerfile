FROM node:16

RUN apt update && apt install build-essential -y
WORKDIR /app
COPY . .
RUN yarn install
CMD ["node", "index"]