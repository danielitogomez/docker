```sh
docker build . -t ssh-server-docker &&  docker run -it -d -p 22:22 ssh-server-docker
```