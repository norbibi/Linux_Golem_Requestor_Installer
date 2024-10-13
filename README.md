<h1 align="center"> Golem Requestor - Linux Installer </h1>

## Why this installer?
I wrote this installer to make it easier to install/update & manage the Golem Requestor daemon for Linux.
Indeed, initially, you have to:
- Download the latest Yagna binaries on the Golem repository.
- Extract them somewhere on your system.
- Add the path to the Path environment variable.
- Create the app-key.
- Request test tokens.  
 
Systemd is used to wrap Yagna daemon as a Windows service.

**Thus, this tool makes it possible to automate the installationof the daemon.**  
**Once installed, no need to worry about the daemon anymore, it is launched automatically, just start your application.**  
  
## How to use:  
- Download ZIP archive and extract (or clone) this repository somewhere on your system.  
- Launch install_grs.sh script.
- Launch GolemRequestorService.
- Select option 1 to install.
  
Additional actions are available to manage the service.  
To update Yagna just relaunch GolemRequestorService and select option 1 (as for initial installation).  
  
<p align="center">
<img src="resources/grs.png" width="100%"> 
</p>
