# How to locally host any website 
Steps 
- change ip port number 8080 form listen (httpd.conf) - of Appache
- find ip address : ipconfig
- change the ServerName in (httpd.conf) and write ur ip address. :8080
- in httpd-xampp.conf search phpMyAdmin replace (local) with all granted where Require is written. 
- xampp > confiq > Server Setting (Main Port = 8080)
- control Panal : check the appache http Server tick both public and private.
- 0.0.0.0:8080/project_name 
## Reference Video 
[a link](https://www.youtube.com/watch?v=aZDAd3nT4jQ)
