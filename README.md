# CollectionsDB

## Installing Development Pre-Requisites

Install [Docker](https://www.docker.com/).

## Installing The Project for Development

Clone the repository:

```bash
git clone -o upstream git@github.com:Medology/api.raven.com.git
cd api.raven.com
```

Start the raven Docker Containers:

```bash
docker-compose up
```

The first time you run this, it will need to build/fetch each of the images. This can take a few minutes depending on your internet connection speed.

You will see the output of the various LEMP stack components in the terminal window:

web_1 - Nginx
db_1 - MySQL
app_1 - PHP

Once you see the db_1 service output "/usr/sbin/mysqld: ready for connections.", then you can open the browser on your machine and go do `localhost` to view the site. You can also visit `localhost/phpinfo.php` to get information about the PHP installation.
