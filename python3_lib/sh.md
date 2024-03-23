```shell
docker build . -t python3_lib:v4
```

```shell
docker run -itd --rm --name python3_lib_v4 --network frpc_nas python3_lib:v4
```

```shell
docker exec -it python3_lib_v4 /bin/bash
```












