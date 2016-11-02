# Munin_Application_Availability_Check
This munin plugin is gonna check 2 parts, the httpd service and the rest api response and returns the result in a graph in munin interface.

# Installation

1- Put the perl script under
/usr/share/munin/plugins/Munin_Application_Availability_Check

2- Create a symbolic link under /usr/share/munin/plugins/Munin_Application_Availability_Check
ln -s /usr/share/munin/plugins/Munin_Application_Availability_Check  /etc/munin/plugins/Munin_Application_Availability_Check 

3- Restart munin-node
service munin-node restart

Enjoy
