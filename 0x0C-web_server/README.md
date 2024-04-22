# 0x0C. Web server
What is Nginx?

Nginx is a free, open-source, high-performance web server and reverse proxy. It's known for its efficiency, scalability, and stability, making it a popular choice for powering websites and applications.

Prerequisites:

A server machine with a Linux distribution (e.g., Ubuntu, Debian).
SSH access to your server.
Basic understanding of command line and text editing.
Setup Steps: (Note: These are general instructions. The specific commands may vary depending on your Linux distribution.)

Installation:

Update package lists:
Bash
sudo apt update
Use code with caution.
Install Nginx:
Bash
sudo apt install nginx
Use code with caution.
Create a Simple Website:

Create a directory for your website files (e.g., /var/www/your_website).
Create an index.html file with your website content within this directory.
Configure Nginx: (Caution: Editing configuration files can impact server functionality. Proceed with care.)

Locate the default Nginx configuration file (usually in /etc/nginx/nginx.conf).
Edit the configuration to specify the location of your website files (the root directive) and adjust other settings as needed.
Test and Restart:

Save the configuration file.
Test the configuration for syntax errors:
Bash
sudo nginx -t
Use code with caution.
If there are no errors, restart Nginx:
Bash
sudo systemctl restart nginx
Use code with caution.
Access Your Website:

Open a web browser and navigate to your server's IP address or domain name. You should see your website content.
Additional Resources:

Official Nginx Documentation: https://nginx.org/en/docs/
Nginx Tutorial: https://ubuntu.com/tutorials/install-and-configure-nginx
Beginner's Guide to Nginx: https://www.nginx.com/resources/wiki/start/
