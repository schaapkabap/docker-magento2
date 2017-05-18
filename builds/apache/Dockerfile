FROM fballiano/magento2-apache-php

RUN apt update -y && apt upgrade -y && apt install -y \
    vim \
    net-tools

RUN touch /var/log/apache2/php_errors.log
RUN chmod 777 /var/log/apache2/php_errors.log