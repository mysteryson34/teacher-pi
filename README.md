# teacher-pi

Born of necessity, this project makes use of several existing bits of software, including Raspbian Stretch as a headless O.S. and...
 - Apache
 - PHP
 - MySQL
 - Wordpress

Before we can begin customizing the Raspberry Pi for the classroom, we need to setup a LAMP server and install/configure Wordpress.

    sudo apt-get install apache2 php mysql-server php-mysql

This device is created with the intent of simultaneously connecting to multiple students' notebook computers. In order to keep system resources available for this purpose, we will install and interact with the device using the command line. In its normal operating state, the RPi will not connect to display and we will not install a G.U.I.

