# SAII_Infrastructure_Developer_Skills_Task
A skills assessment for an Infrastructure Developer position


Deployment Script Task
###The Problem

At the City of Asheville, we maintain a lot of web applications that provide services to citizens and city employees alike. These web apps run in a variety of environments, both on Linux and Windows, and vary greatly in complexity. Currently, deploying a new web application requires a lot of manual work. As you know, spinning up new servers and installing the proper software on those servers can be tedious, time-consuming, and error-prone. To avoid this, we would like to begin scripting the deployment of new servers and web applications at the City of Asheville. In order to evaluate deployment methodologies, we have decided to use a standard Wordpress deployment as a gauge since it incorporates most of the components common to any web application deployment (e.g. setting up a web server, a database, an environment, and launching the app). 

###The Task

Write a script that will deploy a Wordpress website to a Linux server running Apache, PHP, and MySQL on Amazon EC2. We don’t expect you to be an expert in Wordpress, or even have any experience working with Wordpress. Instead, we would like for you to demonstrate that you can deploy a web application to AWS EC2. We’re not looking for you to reinvent the wheel, so feel free to use or borrow other code, recipes, playbooks, etc.

######The script should, at a minimum, do the following:
1. Create a new Linux instance on Amazon EC2 (you choose the flavor)
a.We should be able to SSH to the new instance after running the script
2. Install and configure Apache
3. Install and configure MySQL 
  * Create a database
  * Create a root user and password
  * Grant appropriate privileges to that user
4. Install and configure PHP
5. Install and configure Wordpress 
6. 
Nice to haves, but not essential …
1. Pass in configuration for wp_config.php or the wp_config.php file itself.
2. Pass in a database backup file to rebuild an existing wordpress database as part of the deployment.

###Rules

Keep it simple. We are not looking for a finished product but want to learn a little more about your skills and how you approach problems. Think of your delivery as something “minimal” that is on the road to awesome. You may submit results via GitHub, Google Drive, DropBox, (or any similar file sharing service) or any way that you prefer.
* You may use, borrow anything you want but the work should be done by you.
* You may email us with any questions. ccarlyle@ashevillenc.gov or use this repo’s issues.


###The Deliverables

1. A deployment script
2. Documentation on how to run/configure the deployment script
3. 
Please complete your submission by {} -  Early submissions are welcome!  

###Resources
[Tutorial: Hosting a WordPress Blog with Amazon Linux](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/hosting-wordpress.html)

[How to install a Wordpress site](http://codex.wordpress.org/Installing_WordPress)

###Have fun!

