Microservices project made up of 1 frontend service and 2 backend services: products & shopping-cart

#### To build the projects
    docker build -t ms-frontend:1.0 frontend
    docker build -t ms-products:1.0 products
    docker build -t ms-shopping-cart:1.0 shopping-cart

#### To start with docker-compose 

    docker-compose -d up
