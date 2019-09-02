
Vagrant.configure("2") do |config|

  config.vm.box = "Microsoft/EdgeOnWindows10"
  config.vm.box_version = "1.0"
  config.disksize.size = '60GB'
  #Configurar carpetas compartidas
  #config.vm.synced_folder "D:/compartida", "C:/Users/IEUSer/compartida", type: "smb"

  config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    vb.gui = true

    # Customize the amount of memory on the VM:
    vb.memory = "6144"
    vb.cpus = "4"
    vb.customize ["modifyvm", :id, "--vram", "128"]

  end

end
