```shell
docker build . -t python3_lib:v4
```

```shell
docker container stop python3_lib_v4

docker run -itd --rm \
  --name python3_lib_v4 \
  --network frpc_nas \
  -v /share/ssd/program/download-util/pixiv.net/download_pixiv:/app \
  python3_lib:v4


docker run -itd --rm \
  --name python3_lib_v4 \
  python3_lib:v4
```

```shell
docker exec -it python3_lib_v4 /bin/bash
```












