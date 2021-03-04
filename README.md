# Setup 

- conda create -n fastapicrud python=3.8.1 pytest=5.3.2 

- docker-compose up -d --build

- Navigate to http://localhost:8002/ping

- Interactive API documentation http://localhost:8002/docs


# Testing

- docker-compose exec web pytest 