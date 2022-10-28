FROM ubuntu

RUN apt update -y
RUN apt upgrade -y
RUN DEBIAN_FRONTEND=noninteractive TZ=Etc/UTC apt-get -y install tzdata
RUN apt install -y apache2 php libapache2-mod-php php
COPY index.php /var/www/html/
CMD apachectl -D FOREGROUND