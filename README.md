# Linux Server Configuration
## IP address and SSH Port
IP: 35.161.236.174
SSH Port: 2200

## URL
URL:`http://ec2-35-161-236-174.us-west-2.compute.amazonaws.com`

## Packages Installed
- apache2
- libapache2-mod-wsgi
- postgresql
- git
- python-flask-sqlalchemy
- python-httplib2
- python-oauth2client

## Configurations Made
1. Create a new user `grader`
2. Add `grader` to sudoer list
3. Install public key for `grader`
4. Disable remote SSH login for `root` user
5. Set new password for `root`
6. Update and upgrade currently installed packages
7. Change SSH port from 22 to 2200
8. Deny all incoming traffic from firewall
9. Allow all outgoing traffic from firewall
10. Open port 2200/tcp, 80 and 123 on the firewall
11. Set the timezone to UTC
12. Configure Apache to serve a Python mod_wsgi application
13. Create a PostgreSQL normal user `catalog`
14. Create a database `catalog`
15. Clone Catalog GitHub repository to the server
16. Change the permission of the `.git` folder to 700
17. Change the `client_secrets.json` file to its full path
18. Add the server IP and URL to Google Sign-in allowed Javascript origin and re-direct list.
19. Download the new Client Secrets JSON file
20. Add `127.0.1.1 ip-10-20-26-140` to /etc/hosts file 

## Additional Resources Used
- https://www3.ntu.edu.sg/home/ehchua/programming/webprogramming/Python3_Flask.html
- https://help.ubuntu.com/community/UbuntuTime
- http://www.howtogeek.com/193811/how-to-change-how-long-sudo-waits-before-it-prompts-you-again/
- https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-an-ubuntu-14-04-vps
- https://help.ubuntu.com/lts/serverguide/httpd.html
- https://wiki.archlinux.org/index.php/SSH_keys

## Credentials
root password: 3QX)8C.k>H_?,J_M

grader password: zWFu)>4J+9N*D~'n

PostgreSQL catalog password: Ch8rUDnBQ9vHq5FT