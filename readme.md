JELYLL WITH DOCKER FOR DEV
====

## PREPARE
* In case you have jekyll app, place it into ./workspace/
* If you do not have it, let's set up app

## RUN
```
docker-compose up -d --build
```

### SET UP APP
```
$ docker exec -it jekyll_jekyll_1 bash
$ jekyll new . --force
$ jekyll build
```

## START&STOP
```
docker-compose start
docker-compose stop
```

## DELETE
* After delete, also delete ./.data/db/
* After delete, also delete ./.html/

```
docker-compose down
```

## STATUS
```
docker ps -a
```

## LOG
```
docker-compose logs -f
```

## SEE
* [Jekyll](http://localhost:4000/)

## REFERENCE
* [jekyll/jekyll](https://hub.docker.com/r/jekyll/jekyll/)
