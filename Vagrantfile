Vagrant.configure("2") do |config|
  config.vm.define "m01" do |m01|
    m01.vm.box = "bento/ubuntu-16.04"
    m01.vm.hostname = 'm01'
    m01.vm.box_url = "bento/ubuntu-16.04"
    m01.vm.network :private_network, ip: "192.168.56.101"
   # m01.vm.provision :shell, inline: "sed 's/127\.0\.0\.1.*agent.*/192\.168\.56\.101 agent/' -i /etc/hosts"
  #  m01.vm.network :public_network, bridge: "802.11n USB Wireless LAN Card", ip: "192.168.100.20"
  #  m01.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1"
        m01.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 1024]
      v.customize ["modifyvm", :id, "--name", "m01"]
    end
  end

  config.vm.define "m02" do |m02|
   
    m02.vm.box = "bento/ubuntu-16.04"
    m02.vm.hostname = 'm02'
    m02.vm.box_url = "bento/ubuntu-16.04"
    m02.vm.network :private_network, ip: "192.168.56.102"
   # m02.vm.provision :shell, inline: "sed 's/127\.0\.0\.1.*agent.*/192\.168\.56\.102 agent/' -i /etc/hosts"
   # m02.vm.network :public_network, bridge: "802.11n USB Wireless LAN Card", ip: "192.168.100.21"
   # m02.vm.network "forwarded_port", guest: 80, host: 8081, host_ip: "127.0.0.1"


    m02.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 1024]
      v.customize ["modifyvm", :id, "--name", "m02"]
    end
  end

  config.vm.define "m03" do |m03|
   
    m03.vm.box = "bento/ubuntu-16.04"
    m03.vm.hostname = 'm03'
    m03.vm.box_url = "bento/ubuntu-16.04"
    m03.vm.network :private_network, ip: "192.168.56.103"
   # m03.vm.provision :shell, inline: "sed 's/127\.0\.0\.1.*agent.*/192\.168\.56\.103 agent/' -i /etc/hosts"
   # m03.vm.network :public_network, bridge: "802.11n USB Wireless LAN Card", ip: "192.168.100.21"
   # m03.vm.network "forwarded_port", guest: 80, host: 8081, host_ip: "127.0.0.1"


    m03.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 1024]
      v.customize ["modifyvm", :id, "--name", "m03"]
    end
  end

  config.vm.define "m04" do |m04|
   
    m04.vm.box = "bento/ubuntu-16.04"
    m04.vm.hostname = 'm04'
    m04.vm.box_url = "bento/ubuntu-16.04"
    m04.vm.network :private_network, ip: "192.168.56.104"
   # m04.vm.provision :shell, inline: "sed 's/127\.0\.0\.1.*agent.*/192\.168\.56\.104 agent/' -i /etc/hosts"
   # m02.vm.network :public_network, bridge: "802.11n USB Wireless LAN Card", ip: "192.168.100.21"
   # m02.vm.network "forwarded_port", guest: 80, host: 8081, host_ip: "127.0.0.1"


    m04.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 1024]
      v.customize ["modifyvm", :id, "--name", "m04"]
    end
  end

end

