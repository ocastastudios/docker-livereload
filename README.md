# Docker Livereload

Based on [node-livereload](https://github.com/napcs/node-livereload)

To use, add this to your `docker-compose.yml` file:
```
livereload:
  image: ocasta/livereload
  ports:
    - "35729:35729"
  volumes:
    - /your/watch/directory:/usr/src/livereload-watch
```
