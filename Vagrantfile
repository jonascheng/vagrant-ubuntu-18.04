Vagrant.configure("2") do |config|
  config.vm.box = "boxomatic/ubuntu-18.04"
  config.vm.box_version = "20210723.0.1"

  config.vm.define "web" do |node|
    node.vm.network "private_network", type: "dhcp"
  end
end
