FROM    node:18.16.0-alpine3.18
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install 
COPY . .
EXPOSE 3001
CMD ["npm", "start"]