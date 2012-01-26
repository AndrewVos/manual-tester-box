Vagrant::Config.run do |config|
  config.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  config.vm.box = "ubuntu-lucid-32"
  config.vm.provision :shell, :path => "provision"

  #config.vm.boot_mode = :gui
end
