apt-get install collectd (to install collectd)

Steps to install collectd GUI: (default collectdi_interval is 10 minutes)
apt-get install lighttpd  (light https server not require lot of configurations)
apt-get install git php php-cgi      (additional dependencies)

edit /etc/php/7.0/cgi/php.ini   --> uncommenct cgi.fix line

sudo lighttpd-enable-mod fastcgi
sudo lighttpd-enable-mod fastcgi-cgi

Finally under /var/www/
put "sudo git clone http://git.nethuis.nl/pub/cgp.git"
then "service lighttpd restart"




MORE EXPLORATION:
integrate collectd with nagios
explore MRTG toolkit (multiRouterTrafficGrapher)

