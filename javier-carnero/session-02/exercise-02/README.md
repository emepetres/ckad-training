# S02 Exercise II Solution

Kubernetes exercise deploying a Wordpress and Drupal instances connected to an instance of MariaDB.

## What's implemented

* Job for backing up a WordPress Database.
* It uses a volume for the backup.
* It uses mysqldump command.

## How to run

With *kubectl configured*, do `./command.bash` to start the app. The script will print the URLs to access.