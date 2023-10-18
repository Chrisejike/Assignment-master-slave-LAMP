# Assignment due 18th October.

--- 
**Script to install master and slave ubuntu vagrant machine, creating a user - "altschool"**

**Master and slave are set to not more than 1024MB of memory, and 2 CPUs, and to have LAMP stack installed on both machines**
**Apache restarts after installation of different versions and subsequent configuration. permissions for /var/www is set to owner and group "www-data:www-data"**

**Master machine is using ubuntu/focal64 image, public network with IP of 192.168.50.60; configured to update and upgrade, then to install an SSH Pass, and allow password authentication by external user. It also restarts sshd service, and installs avahi daemon**

**Master machine creates sudo user "altschool, create an SSH key for "altschool", set only the user to be able to ssh into the machine without password, copy a file named /mnt from "altschool" to the slave machine**

**Slave machine "slave" using ubuntu/focal64 image, private network with a constant ip of 192.168.50.61**

**Slave machine is also configured to update and upgrade, then to install an SSH Pass, and allow password authentication by external user. It also restarts sshd service, and installs avahi daemon**



