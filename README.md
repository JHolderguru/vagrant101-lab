# Running the lab test ,usually this will be a pvt rerouted environment

#sudo-apt-update

#then--> sudo apt-get install nginx -y

#sudo systemctl restart nginx

#other commands
#### vagrant init
	Instead, you could try
	$ vagrant init hashicorp/precise32
	$ vagrant up

#### vagrant up (always the first)
#### vagrant ssh (get into the VM)
		#### sudo apt-get update
		#### sudo apt-get install nginx -y
		#### systemctl restart nginx
		--if ### vagrant destroy to get rid
####permission denied?