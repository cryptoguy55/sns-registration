## FLOW

#install
	- setup the Node.js
	Go to the Node.js Downloads page(https://nodejs.org/en/download)
	Download Node.js for macOS by clicking the "Macintosh Installer" option
	Run the downloaded Node.js .pkg Installer
	Run the installer, including accepting the license, selecting the destination, and authenticating for the install.
	You're finished! To ensure Node.js has been installed, run node -v in your terminal 
	
	- install packages
	run the 'npm install' on terminal


1. look up the domain 

	node .\index.js lookup_domain -n <domain>

2. regist domain
	
	node .\index.js register_domain -n <domain>

2. transfer domain
	
  	node .\index.js transfer_domain -n <domain> -d <destination>
