<h1 align="center"> Golem Requestor - Linux Installer </h1>

## Why this installer?
I wrote this installer to make it easier to install/update & manage the Golem Requestor daemon for Linux.  
Indeed, initially, you have to:
- Download the latest Yagna binaries in the Golem repository.
- Add the path to the Path environment variable.
- Create the app-key.
- Request test tokens.  

In addition, you need to first launch the daemon in a dedicated terminal before running your application.  
Systemd is used to wrap Yagna daemon as a Linux service.

**Thus, this tool makes it possible to automate the installation of the daemon.**  
**Once installed, no need to worry about the daemon anymore, it is launched automatically, just start your application.**  
  
## How to use:  
```
git clone https://github.com/Linux_Golem_Requestor_Installer.git
cd Linux_Golem_Requestor_Installer
sudo ln -s $PWD/GolemRequestorService /usr/bin/GolemRequestorService
GolemRequestorService
```
Then select option 1.
  
Additional actions are available to manage the service.  
To update Yagna just relaunch GolemRequestorService and select option 1 as for initial installation.  
  
<p align="center">
<img src="resources/grs.png" width="100%"> 
</p>
