Nginx Commands

## Update and Upgrade VM

- Update VM
````
sudo apt update
````
- Upgrade VM
````
sudo apt upgrade -y
````

## Install nginx

- Install nginx
````
sudo apt install nginx -y
````
- Setup reverse proxy
````
sudo apt install sed
````
````
sudo sed -i "s/try_files \$uri \$uri\/ =404;/proxy_pass http:\/\/localhost:3000\/;/" /etc/nginx/sites-available/default
````
- Start nginx
````
sudo systemctl start nginx
````
- Restart nginx
````
sudo systemctl restart nginx
````
- Enable nginx
````
sudo systemctl enable nginx
````