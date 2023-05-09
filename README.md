# clojure-debian
you must build this Dockerfile because this Docker image is not shared in DockerHub. run this command to build in repo

```bash
docker image build -t clojure-debian:latest .
```

## usage
```bash
# this command enter into clojure repl
docker run --rm -it clojure-debian clojure
```
