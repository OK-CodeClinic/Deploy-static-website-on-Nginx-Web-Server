# Host Sample WebSite on Nginx Server

This task give me the general knowledge how to use Nginx Server to host a website. 
This example also shows how to interact with Nginx and how to configure Nginx. Configuration is optionl, since a default configuration is included in workspace-full.

## Author

- [Kehinde Omokungbe](https://www.github.com/OK-CodeClinic)
### Steps
1. ```sudo apt install nginx``` - Install nginx in the Linux Server
2. ```systemctl start nginx``` - To start nginx in the Linux Server
3. Download sample html/css from www.tootemplate.com to ```/tmp``` folder. Using ; ```wget filename.zip```
4. Unzip the file; Using ```unzip filename```
5. Copy unzipped file to nginx html location; using```cp -r filename/* /var/www/html```
6. Retart nginx; Using ```systemctl restart nginx```
7. Validate on your web browser using your ip address;
```ifconfig``` or 
```ip addr show```


### Command to try; 
- ```Sytemctl start nginx``` - start Nginx (it's started automatically on workspace launch)
- ```systemctl stop nginx``` - stop Nginx
- ```systemctl restart nginx``` - reload Nginx config
- ```systemctl is-enable nginx``` - To validate if nginx is enabled
- ```gp open /etc/nginx/nginx.conf``` - Open nginx.conf
- ```gp open /var/log/nginx/access.log``` - Open access.log
- ```gp open /var/log/nginx/error.log``` - Open error.log
- ```multitail /var/log/nginx/access.log -I /var/log/nginx/error.log``` - View and follow logs in Terminal


### Aknowledgment

Please, patronize www.tootemplate.com, they have awesome html and css sample website templates
## Purpose

This is for learning purpose only.


