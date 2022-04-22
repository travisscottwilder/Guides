This is for raspberry pi ubuntu 20 (ubuntu-20.04.4-preinstalled-server-arm64+raspi.img)


	sudo apt update -y;sudo apt upgrade -y;sudo apt autoremove -y;sudo shutdown -h now;
	
Log back in after reboot
	
	sudo apt update -y;sudo apt upgrade -y;sudo apt autoremove -y;curl https://download.argon40.com/argon1.sh | bash;curl https://raw.githubusercontent.com/RunOnFlux/fluxnode-multitool/master/multitoolbox.sh > installflux.sh;chmod +x installflux.sh;
	
  
  
	./installflux.sh;
		-> option 1 [need zelcore username]
	./installflux.sh;
		-> option 2 [need zelcore mining signature, tx, and id info]
