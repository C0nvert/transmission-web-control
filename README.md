THIS IS A FORK!!
Credits to https://github.com/ronggang/transmission-web-control

## Support Transmission Version
* Transmission 2.40 and above (RPC version: 14 and above)

## Browsers support
* A browser which supports HTML5. (Chrome 15.0.874，Firefox 8.0.1，IE 9.0.8112，Opera 11.52 etc.)

## Features
* Add torrent files or URLs
* Drag-and-drop to add torrent files
* Modify Transmission settings online (Download folder, Speed limit, Port, etc.)
* Pause / resume / recheck selected or all torrents
* View the current torrents status (Files, Peers, Trackers etc.)
* View Statistics (Cumulative/Current)
* Pagination
* Set files priority
* Change the torrent download directory
* Trackers list
* Multi-language support. Supported-languages: [Click Me](Supported-languages#currently-supported-languages).
* Add support for `Synology NAS Download Station`; By - @hitechbeijing

## Special feature
* Support data folder display in the navigation bar.
* Support "user label" feature, you can use it to classify torrent.
* Automatically matches data directory. [What's this?](https://github.com/C0nvert/transmission-web-control/issues/220#issuecomment-382931740)


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


