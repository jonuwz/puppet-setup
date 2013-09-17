puppet-setup
============

This works on CentOS / RHEL 6.4

Run this script, and it'll

a) install puppet-server, puppet-dashboard and puppet  
b) install and configure httpd and passenger  
c) configure puppet-server and puppet-dashboard for use behind httpd/passenger  
d) setup storeconfigs  
e) setup useful values for puppet.conf  
f) configure iptables  

SELinux remains enforcing.

To-Do
=====

Add Mcollective (maybe) and puppetdb
