FROM ubuntu

RUN apt-get update -y
RUN apt-get install -y mariadb-server
EXPOSE 3306
CMD var=$(openssl rand -base64 15)
CMD service mariadb start && tail -f /dev/null