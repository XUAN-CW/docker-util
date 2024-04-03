FROM python:3.10.14-bookworm

# Update package list and install some command
RUN apt-get update -y
RUN apt-get install -y iputils-ping

# pip3
#https://pypi.org/project/pixivpy3/#history
RUN pip3 install pixivpy3==3.7.5
#https://pypi.org/project/elasticsearch/#history
RUN pip3 install elasticsearch==8.12.1
RUN pip3 install beautifulsoup4==4.12.3
RUN pip3 install requests==2.31.0
RUN pip3 install lxml==5.2.0
WORKDIR /app

CMD ["python3"]
