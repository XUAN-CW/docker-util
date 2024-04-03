```shell
docker build . -t python3_lib:v1
```

```shell
docker container stop python3_lib
docker run -itd --rm \
  --name python3_lib \
  --network common_network \
  -v /share/ssd/python3:/app \
  python3_lib:v1

```

```shell
docker exec -it python3_lib /bin/bash
```












