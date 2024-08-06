FROM node:14-alpine
WORKDIR /app
COPY api/package*.json ./
RUN npm install
COPY api/ ./
EXPOSE 4001
CMD ["npm", "run", "start:v2"]

