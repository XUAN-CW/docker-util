```shell
docker build . -t python3_lib:v1
```

```shell
docker run -itd --rm --name python3_lib_v1 --network frpc_nas python3_lib:v1
```

```shell
docker exec -it python3_lib_v1 /bin/bash
```












