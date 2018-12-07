Vagrant.configure("2") do |config|
  config.vm.box = "UCSPE"
  config.ssh.username = "ucspe"
  config.ssh.password = "ucspe"
  config.vm.network "forwarded_port", guest: 80, host: 8081, id: 'ucs_http'
  config.vm.network "private_network",  ip: "10.252.0.3", :name => 'vboxnet5', :adapter => 2
  config.vm.network "private_network",  ip: "10.252.0.4", :name => 'vboxnet5', :adapter => 3

  config.vm.boot_timeout = 300
  config.vm.provider "virtualbox" do |vb, override|
    vb.gui = false
  end

  #config.ssh.host = '10.252.0.3'

end
