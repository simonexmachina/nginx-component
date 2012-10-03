# nginx-component

  Simple Nginx config and scripts for development use

# Installing Nginx on Mac OS X

# 10.7.4

The following worked for me. It's best if you simply ignore the fact that Passenger compiles Nginx 1.2.3 in /opt/nginx even though 1.2.2 is installed by Homebrew in /usr/local/Cellar/nginx :)

	brew install nginx
	gem install passenger
	passenger-install-nginx-module