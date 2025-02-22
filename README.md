# Email Server on Ubuntu LTS

We will try to setup email server with Postfix (MTA), Dovecot (MDA) and Roundcube/Horde as webmail server.

As someone who is coming from years on working with Microsoft Exchange, it was hard for me to find a good replacement for Exchange on Linux. I went through a lot of different combinations on Linux, and this one I’m going to write about today is one of them that I think is worth trying.  

### Before we begin

This is only basic tutorial to get your email server up and running, so please have that in mind. Be also sure to properly secure and configure in detail your email server afterwards.

I will not go through all the details needed for a complete email server environment with this tutorial. I have a plan for the future to explain all the little details you need to put up a web service, here I will just be describing email server setup procedure.

- Configuring hostname and DNS records
- Open Firewall ports
- Certificate Story
	- Postfix certificates
	- Dovecot certificates
- Installing Apache, MariaDB/MySql and PHP
- Installing Postfix
- Test Postfix Mail Server
- Advanced Postfix Configuration (Utilities)
