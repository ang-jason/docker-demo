# Docker demo
Docker demo files can be found and adapted from https://github.com/wardviaene/docker-demo
```
sudo dockerd


cd into the directory

docker build .

```


```
Removing intermediate container 15f6a42d3bc5
 ---> c5e3893ed93d
Successfully built c5e3893ed93d
```

```
docker run -p 3000:3000 -it c5e3893ed93d


using another window

curl localhost:3000
```


```
docker image ls

$ docker login
$ docker tag imageid your-login/docker-demo
$ docker push your-login/docker-demo
```


Push docker image to docker hub
![](https://i.imgur.com/7Unk3Cg.png)
