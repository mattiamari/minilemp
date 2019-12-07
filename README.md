# MiniLEMP
A minimal, dockerized, Nginx + PHP + MariaDB environment for local development.

## Usage
```bash
git clone https://github.com/mattiamari/minilemp
cd minilemp
docker-compose up
```

Then just add some content to the ```www``` directory, open
your browser and navigate to ```http://localhost:9080```.

Access to the sql database is possible through some client (MySQL Workbench, DBeaver, HeidiSQL)
```
host    : localhost
port    : 3306 (default mysql port)
user    : root
password: mysql
```
