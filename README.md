# cmd
Useful Linux Commands

<h3> `fuser` </h3>

  * lists the process that uses the file provided as parameter

  *USAGE*

    1. ```fuser /var/log/nginx.log``` - lists the process using the file `/var/log/nginx.log`
    2. ```fuser -v /var/log/nginx.log``` - provides the verbose output
    3. ```fuser -k /var/log/nginx.log``` - kills the process
