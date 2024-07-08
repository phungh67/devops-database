# How to use this repository

## For MySQL database
- Place ``.cnf`` file under directory ``/etc/mysql/my.cnf``. MySQL will automatic recognize and accept the configuration paramters in this file. Need restart service for new configuration to be applied.
    ```bash
    sudo service mysql restart
    ```

- With galera, just place it in the same location with ``my.cnf`` after installation of Galera packages.

## For redis
- Make a backup of file ``redis.conf`` and replace it with your custimized file.