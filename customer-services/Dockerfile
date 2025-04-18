FROM node:18-alpine
ENV NODE_ENV=production PORT=3005 DB_URL=mongodb://mongodb:27017/cafe
WORKDIR customer-services
COPY . .
RUN npm install
EXPOSE 3005
CMD ["node","index.js"]
