Sets up server from fresh Ubuntu Linux instalation and configures a working
environment for an empty Django project running nginx.

It does not install postgreSQL or elastic search.

* Create a user "vagrant" and add it to the sudoers:

    * sudo adduser vagrant
    * sudo adduser vagrant sudo

* Log in as vagrant and run file:

    * cd /home
    * sudo bash provisions.sh

