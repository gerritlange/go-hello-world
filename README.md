# go-hello-world
A simple hello-world application written in Go to illustrate multi-stage builds in Docker 17.05, and the builder pattern
<h1>This is a little test to showcase CodeShip CI/CD</h1>

`docker build -t single-stage -f Dockerfile.single .`

`docker build -t multi-stage -f Dockerfile.multi .`

```
$ docker images

REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
single-stage        latest              58328409dbf7        2 minutes ago       704MB
multi-stage         latest              9af3c2a2bf40        23 minutes ago      5.54MB
```

😱

[![Codeship Status for gerritlange/go-hello-world](https://app.codeship.com/projects/1762d507-89e0-49c7-b94a-f900c9b86889/status?branch=master)](https://app.codeship.com/projects/418336)