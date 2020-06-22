
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"


   # config.vm.network "forwarded_port", guest: 80, host: 8080,
     # auto_correct: true


#the reverse output will give me an output nto my running machine ,
  config.vm.network "private_network", ip:"192.167.10.111"
#asking Developers to go on an user is not user friendly
#lets give them a host with a letters for them to accecc and view their
#amazing Dev work

#install vagrant pluging
#vagrant installvagrant-hostsupdater
  config.hostsupdater.aliases = ["devissocool.local"]
  
end
