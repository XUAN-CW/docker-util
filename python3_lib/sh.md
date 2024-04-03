```shell
docker container stop python3_lib
docker build . -t python3_lib:v1
```

```shell
docker container stop python3_lib
docker run -itd --rm \
  --name python3_lib \
  --network common_network \
  -v /share/ssd/python3:/app \
  python:3.10.14-bookworm

```

```shell
docker exec -it python3_lib /bin/bash
```

```shell
python3_container_name=python3_$(date "+%Y%m%d_%H%M%S")
docker run -itd --rm --name $python3_container_name python:3.10.14-bookworm
docker exec -it $python3_container_name /bin/bash

```

```shell
python3
from bs4 import BeautifulSoup


pip3 install beautifulsoup4
```











