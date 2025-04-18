FROM node:18-alpine
ENV NODE_ENV=production PORT=3000
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm ci --omit=dev
COPY . .
EXPOSE 3000
CMD ["node","index.js"]
