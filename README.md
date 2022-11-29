# Mongodb simple replica set with 3 replicas 
- docker-compose.yml
  - 3 replica sets
  - orchestrator is another mongodb server:
    - this is mostly to have the mongo command so it can run the initialization of the replica set
    - the container stops post-initialization, so it only runs once at the beggining and it doesn't matter afterwards - still need to test this
- sleeps are important, do not remove them