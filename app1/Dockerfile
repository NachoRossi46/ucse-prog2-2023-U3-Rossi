FROM node:14

WORKDIR /app1

COPY package.json package-lock.json /app1/
RUN npm install
COPY . /app1/

EXPOSE 4000

CMD ["node", "index.js"]
