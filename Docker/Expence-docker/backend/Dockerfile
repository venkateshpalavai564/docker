FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.json .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]