FROM node:14
WORKDIR /app
COPY client/package*.json ./
RUN npm install
COPY client/ ./
CMD ["npm", "start"]
