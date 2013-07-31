jobeet
======

1) Please check your PHP configuration before using this project
by typing "php check_configuration" in the main directory.

2) Create cache/ and log/ directory with all permissions(chmod 777)
in the main directory.

3) Create "jobeet" database in MySQL.

4)while in main directoy:
	-type " php symfony configure:database "mysql:host=localhost;dbname=jobeet" root YourPassword ".
	-type " php symfony doctrine:insert-sql ".
	-type " php symfony doctrine:data-load ".

5)Should now run.

for more information please check http://symfony.com/legacy/doc/jobeet?orm=Doctrine