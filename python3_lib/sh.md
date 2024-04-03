```shell
docker build . -t python3_lib:v1
```

```shell
docker container stop python3_lib
docker container rm python3_lib
docker image rm python3_lib:v1
docker run -itd --rm \
  --name python3_lib \
  --network common_network \
  -v /share/ssd/program/download-util/pixiv.net/download_pixiv:/app \
  python3_lib:v4
```

```shell
docker exec -it python3_lib_v4 /bin/bash
```












