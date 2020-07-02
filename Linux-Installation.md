# Install Transmission Web Control on Linux 
In this guide, we will demonstrate how to install Transmission Web Control on a Linux server through the ssh terminal.
## Prerequisites
1.	Before you complete this tutorial, you should have a root account or a regular, non-root user account on your server with sudo privileges.
2.	Make sure Transmission is installed.
## Install Transmission Web Control
1.	Login as root. For non-root user, you should prefix `sudo` with all commands.
2.	Download the latest script on Github.com.

```
wget https://github.com/ronggang/transmission-web-control/raw/master/release/install-tr-control.sh --no-check-certificate
```

3.	Bash the scipt. 
```
bash install-tr-control.sh
```

Installation will be finished automatically in several minutes according to your network.
You can test if the new UI is up and running by accessing your server's domain name or public IP address in your web browser.

	http://server_domain_name_or_IP:9091

If you see the origin UI, you should reload the page (`Ctrl+F5`) or clean the cache and restart the browser.


## Update
You should update the Transmission Web Control once:
* Transmission is reinstalled or updated.
* New version of Transmission Web Control is released.
If the script is downloaded, bash the script again.
```
bash install-tr-control.sh
```

Or repeat the installation step 2 and 3.