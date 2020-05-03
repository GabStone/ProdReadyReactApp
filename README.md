# Production Ready React Application
create-react-app Production Ready Application

##


### Core technologies:
- React
- NPM
- Docker
- Nginx
- docker-compose

### Running the Server:
- `npm install` to install all required dependencies
- `npm start` to start the local server
- `npm build` to build production release version of the application
- `npm test` to run all configured tests

### Running the Server in Docker
#### Using Docker
- `docker build -f Dockerfile.dev .` to build development docker image
- `docker run -it -p 3000:3000 <IMAGE_ID>` to run the development docker image built above 

#### Using docker-compose
- `docker-compose up --build` to build development container and testing container with mounted volumes

### Production Docker build using NGINX
- `docker build .` to build production docker image
- `docker run -p 80:80 <IMAGE_ID>` to run production docker image built above using NGINX server

## Application Structure
- `App.js` - The entry point to our application.
- `build/` - The production ready folder

## Version
Version: 1.0.0

Created By Gabriel Stone (@GabStone)
