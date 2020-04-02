# nginx et rtmp

Construction du container

```
docker build --tag nginx-rtmp:1.0 .
```

```
docker run -d -p 1935:1935 --name nginx-rtmp .
```

