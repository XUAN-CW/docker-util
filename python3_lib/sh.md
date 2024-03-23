```shell
docker build . -t python3_lib:v3
```

```shell
docker run -itd --rm --name python3_lib_v3 --network frpc_nas python3_lib:v3
```

```shell
docker exec -it python3_lib_v3 /bin/sh
```












