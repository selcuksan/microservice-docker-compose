FROM node:17-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install
COPY index.html .
COPY server.js .

ENV PRODUCTS_SERVICE="products_app_1"
ENV SHOPPING_CART_SERVICE="shopping-cart_app_1"

EXPOSE 3000
CMD ["npm", "start"]
