Purpose: this is a changed version of AppBuilder example "Enums" to test Permission aggregation and share class permission among classes.

How to start:

Insert test data::

    $ python testdata.py

Run it:

    $ export FLASK_APP=app
    
    $ flask fab create-admin
    
    $ flask run

Configuration:

1. At the bottom of `config.py`, the following line should be uncomment before executing `flask fab security-converge` and re-comment the line after the execution.
