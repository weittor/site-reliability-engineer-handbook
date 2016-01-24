# Create init script in CentOS 6

The purpose of this post is to document how to create init script in CentOS 6 to be used with the usual service management commands such as service and chkconfig.

###Introduction

After being somewhat dissatisfied with the service script provided by GlassFish, I decided to learn how to create my own service script to start, stop, and view the status of non-packaged applications.

###Learn Shell Scripting

I began by looking at other service scripts that has been already provided by CentOS such as `/etc/init.d/httpd` and `/etc/init.d/iptables` for ideas.

To help understand the scripts, I had to start learning shell scripting.  A very good tutorial can be found here.
