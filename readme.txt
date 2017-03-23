This file is intended to work with Plesk installations that use WordPress websites.

BASIC USAGE:
sh backup example.org example

EXAMPLE WITH SUBDOMAIN:
sh backup example.org/subdomain example-subdomain

DESCRIPTION:
Will back up /var/www/vhosts/example.org/httpdocs, and the wordpress database:
	./backups/example/httpdocs.zip
	./backups/example/db.sql.zip

You can also backup just files using backupzip, or just the db using backupdb