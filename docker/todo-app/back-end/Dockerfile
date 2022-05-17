FROM node:14-alpine AS todobackend
WORKDIR /back-end
COPY . .
ADD ./node_modules.tar.gz ./
# COPY package*.json ./
# RUN npm install
EXPOSE 3001
CMD ["npm", "start"]