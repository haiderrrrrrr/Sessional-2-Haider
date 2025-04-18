FROM node:18-alpine
ENV NODE_ENV=production PORT=3000
WORKDIR api-gateway
COPY . .
RUN npm install
EXPOSE 3000
CMD ["node","index.js"]
