Owncloud
========

This template installs owncloud with mariadb and memcached.

Note that there are no ports specified by default with the idea to use something
dynamic like the load-balancer.

Usage
-----

After you installed the template and accessed the webclient you'll need to
manually configure the database server clicking on `Storage and database`
just below the registration form.

Then choose `MySQL/MariaDB` and fill the below form as follows:

- **User:** `owncloud`
- **Pass:** `owncloudpwd`
- **DB:** `owncloud`
- **Host:** `db`
