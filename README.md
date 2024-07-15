# Test Server con Mock data per API REST

- https://hub.docker.com/r/dotronglong/faker
- https://github.com/dotronglong/fake
- https://github.com/dotronglong/faker/wiki/Complete-Schema
- https://medium.com/@dotronglong/set-up-fake-api-in-minutes-with-docker-dfffebe264b0


## Config

Configura i file JSON dentro la cartella `mocks`.


## Run 

`docker run --rm -p 3030:3030 -v $PWD/mocks:/app/mocks dotronglong/faker:stable`

### docker-compose

`docker-compose up -d --build`


## Test 

Esegui il file `test.rest`

