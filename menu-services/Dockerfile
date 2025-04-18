FROM node:18-alpine
ENV NODE_ENV=production PORT=3001 DB_URL=mongodb://mongodb:27017/cafe
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm ci --omit=dev
COPY . .
EXPOSE 3001
CMD ["node","index.js"]
