# Nest Docker app example
An example of a NestJS application with Docker

## Prerequisites

Install nestJS CLI
```
npm i -g @nestjs/cli
```
## Installation
1. Clone this project
```
git clone https://github.com/jlsubia404/nest-docker-app.git
```
### Run locally
1. Run
```
npm install
```
2. Run
```
npm run start
```
3. Open your browser at http://localhost:3000

### Run in a container
1. Run 
```
docker-compose up
```

### Run in debug mode
1. Locally
```
npm run start:debug
```
2. In a container
``` 
docker-compose -f docker-compose.debug.yml up
```