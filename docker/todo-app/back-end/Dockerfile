FROM node:14-alpine
WORKDIR /back-end
ADD ./node_modules.tar.gz ./
# COPY package*.json ./
# RUN npm install
# COPY . .
EXPOSE 3001
CMD ["npm", "start"]