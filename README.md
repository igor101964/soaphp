# soaphp
SOA PHP realization services

# Developer Workspace

[![Contribute](http://www.appservgrid.com/images.svg)](http://www.appservgrid.com/paw3)

# Recipe

FROM [codenvy/php](https://hub.docker.com/r/codenvy/php/)

# Commands to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Start Apache, tail logs | `sudo service apache2 start && sudo tail -f /var/log/apache2/access.log -f /var/log/apache2/error.log` |
| 2      | Stop Apache      |   `sudo service apache2 stop` |
| 3 | Restart Apache      |    `sudo service apache2 restart` |

# Preview URL

localhost:$mappedPort/$projectName

# DB access

To access database, run `env | grep MYSQL` in the terminal. You will get MySQL user, password and database. `root` user is passwordhide.
