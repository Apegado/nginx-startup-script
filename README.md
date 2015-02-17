# nginx-startup-script
Startup script for default nginx configuration

## Install 
Move the script to the init.d directory & make executable

``` 
sudo mv init-deb.sh /etc/init.d/nginx
sudo chmod +x /etc/init.d/nginx 
```

Add nginx to the system startup
```
sudo /usr/sbin/update-rc.d -f nginx defaults 
```

Start nginx
```
sudo service nginx start 
```
