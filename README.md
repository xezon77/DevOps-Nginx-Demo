# This a Demo script for Nginx 

This script helps you install Nginx on linux & then show a demo webpage 

# The script 

sudo apt-get update 

sudo apt install nginx 

sudo systemctl start nginx 

sudo systemctl enable nginx 
# So that when the system restarts nginx will also get restarted 

# The webpage is kept at this '/var/www/nginx' location.
You can check for Welcome to Nginx message by searching your local system's ip on any web browser after starting the nginx 

Happy learning...
