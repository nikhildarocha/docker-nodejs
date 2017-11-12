# docker-nodejs
Containerised Node.js applications
For Windows Users:
 Run the quickstart terminal.
 Go to the path where the docker file for the app exists.
 run a docker build. Ex docker build -t 'demo:nodejs-app' .
 run a docker images to see that your image is there.
 run a docker run -p 49160:8080 -d demo:nodejs-app
