## apache-php
**Apache Server** with **PHP** running on **Ubuntu 14.04** using **Docker**

Use the following command below to run in Docker

`docker run -d -t -p 80:80 starkfell/apache-php`

Use the following command to attach run commands within the Container after it is running

`docker exec -ti <CONTAINER_ID> /bin/bash`
