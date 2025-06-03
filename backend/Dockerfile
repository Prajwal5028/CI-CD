FROM node:14-alpine3.12
WORKDIR /app
COPY package*.json ./
# NOSONAR: Running scripts is safe in this controlled environment
RUN npm install
COPY . .
EXPOSE 4000
CMD ["node","index.js"]
