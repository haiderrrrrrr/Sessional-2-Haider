FROM node:18-alpine
ENV NODE_ENV=production PORT=3002 DB_URL=mongodb://mongodb:27017/cafe
WORKDIR order-services
COPY . .
RUN npm install
EXPOSE 3002
CMD ["node","index.js"]
