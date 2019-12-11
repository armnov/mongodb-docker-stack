# mongodb-docker-stack
Run mongodb docker container using stack.yaml for local development purposes. 
Manage mongodb databases with mongo-express.

The project only contains a single stack.yaml file which should be used as a reference.

to run the stack:

1) docker-compose -f stack.yaml
2) Open web browser and go to http://localhost:8081 to access mongo-express
3) Create a new database to test mongodb db persistance
4) stop mongo container > docker container stop mongo
5) run mongo container again > docker container start mongo
6) open mongo-express to see the if the dbs are still there.
