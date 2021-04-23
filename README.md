Install the NetHunter-Store app from https://store.nethunter.com

Installation NetHunter

From the NetHunter Store, install Termux, NetHunter-KeX client, and Hacker’s keyboard Note: The button “install” may not change to “installed” in the store client after installation - just ignore it. Starting termux for the first time may seem stuck while displaying “installing” on some devices - just hit enter.

Open Termux and type Commands for termux:-

$ termux-setup-storage

$ pkg update && pkg upgrade && pkg install git -y 

$ pkg install wget

$ wget -O install-nethunter-termux https://offs.ec/2MceZWr

$ chmod +x install-nethunter-termux

$ ./install-nethunter-termux


Usage:
Open Termux and type one of the following:

Command	                       To
nethunter	                            start Kali NetHunter command line interface
nethunter kex passwd          	 configure the KeX password (only needed before 1st use)
nethunter kex &	               start Kali NetHunter Desktop Experience user sessions
nethunter kex stop	               stop Kali NetHunter Desktop Experience
nethunter <command>	  run in NetHunter environment
nethunter -r	               start Kali NetHunter cli as root
nethunter -r kex passwd	  configure the KeX password for root
nethunter -r kex &	               start Kali NetHunter Desktop Experience as root
nethunter -r kex stop	  stop Kali NetHunter Desktop Experience root sessions
nethunter -r kex kill 	  Kill all KeX sessions
nethunter -r <command>	  run <command> in NetHunter environment as root
