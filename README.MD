https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

In one of the instructions it says you need to supply your username. That is the username of your docker hub account.

docker run -p 49160:8080 -d leejjon/node-web-app

curl -i localhost:49160

after this, use docker start <container id> and docker stop <container id>
