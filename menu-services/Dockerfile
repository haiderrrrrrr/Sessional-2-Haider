FROM node:18-alpine
ENV NODE_ENV=production PORT=3001 DB_URL=mongodb://mongodb:27017/cafe
WORKDIR menu-services
COPY . .
RUN npm install
EXPOSE 3001
CMD ["node","index.js"]
