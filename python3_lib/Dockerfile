FROM python:3.12.2-bookworm


# Update package list and install iputils-ping for the ping command
RUN apt-get update && \
    apt-get install -y iputils-ping && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /usr/src/app

#https://pypi.org/project/pixivpy3/#history
RUN pip3 install pixivpy3==3.7.5
#https://pypi.org/project/elasticsearch/#history
RUN pip3 install elasticsearch==8.12.1


CMD ["python3"]
