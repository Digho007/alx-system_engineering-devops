Tasks
Simple web stack: descripes about simple web infrastructure,a single server with a LAMP stack.
Distributed web infrastructure: 2 servers 1 web server (Nginx) 1 application server 1 load-balancer (HAproxy) 1 set of application files (your code base) 1 database (MySQL)
Secured and monitored web infrastructure 3 firewalls 1 SSL certificate to serve www.foobar.com over HTTPS 3 monitoring clients (data collector for Sumologic or other monitoring services)
Scale up 1 server 1 load-balancer (HAproxy) configured as cluster with the other one Split components (web server, application server, database) with their own server
