IP Address:  52.27.38.159
SSH Port: 2200
URL for App:  http://ec2-52-27-38-159.us-west-2.compute.amazonaws.com/


Installed apps: 	Updated all installed apps and installed the follwoing.
	VirtualEnv - configured virtual enviroment
	Flask 
	Python
	Pip Used to install the following
		Sql Allchemy
		Google OAuth2
		Pysocopg2
	Git - installed and used to sync ReadMe.md
	Apache - Created new Virtual host for port 80.
	UFW - restricted acces to all ports except for NPT/123, HTTP/80 and SSH/2200
	Postgresql - crated user catalog to acecss new database itemcatalog
	Fail2ban - Bans repeated failed logins to server

	Configured apps:
		Added cron job to run update script daily
		Fail2ban configured for servers firewall

Consulted Resources:
	
	https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
	https://www.digitalocean.com/community/tutorials/an-introduction-to-securing-your-linux-vps
	https://www.digitalocean.com/community/tutorials/how-to-protect-ssh-with-fail2ban-on-ubuntu-12-04
	https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf

