FROM node:18-alpine
ENV NODE_ENV=production PORT=3004 DB_URL=mongodb://mongodb:27017/cafe
WORKDIR inventory-services
COPY . .
RUN npm install
EXPOSE 3004
CMD ["node","index.js"]
