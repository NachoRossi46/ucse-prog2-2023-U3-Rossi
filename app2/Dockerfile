FROM node:14

WORKDIR /app2

COPY package.json package-lock.json /app2/
RUN npm install
COPY . /app2/

EXPOSE 4001

CMD ["node", "index.js"]
