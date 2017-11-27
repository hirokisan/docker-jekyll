JELYLL WITH DOCKER FOR DEV
====

## PREPARE
* In case you have jekyll app, place it into ./workspace/
* If you do not have it, let's set up app

### SET UP APP
```
$ docker exec -it jekyll_jekyll_1 bash
$ jekyll new . --force
$ jekyll build
```

## SEE
* [Jekyll](http://localhost:4000/)

## REFERENCE
* [jekyll/jekyll](https://hub.docker.com/r/jekyll/jekyll/)
