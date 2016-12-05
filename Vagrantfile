Vagrant.configure("2") do |config|
  config.vm.define "debian-test-1" do |config|
    config.vm.box = "deb/jessie-amd64"
    config.vm.hostname = "debian-test-1"
    config.vm.network "public_network"
  end
  config.vm.define "debian-test-2" do |config|
    config.vm.box = "deb/jessie-amd64"
    config.vm.hostname = "debian-test-2"
    config.vm.network "public_network"
  end
end
