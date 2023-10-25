FROM centos:7
MAINTAINER kdetony
RUN yum -y update &&\
    yum -y install python3 python3-pip mariadb telnet net-tools
RUN pip3 install pymysql
WORKDIR /app
ADD app.py .
CMD ["python3", "/app/app.py"]
