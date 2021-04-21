Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"

  config.vm.network "forwarded_port", guest: 3306, host: 3306
  
  config.vm.provision "shell", inline: <<-SHELL
    apt-get update && \
    apt-get install -y mysql-server
  SHELL
end
