Vagrant.configure("2") do |config|
  config.vm.define "kali" do |kali|
    kali.vm.box = "kalilinux/rolling"
    kali.vm.hostname = 'kali'
    kali.vm.network :private_network, ip: "172.20.10.10"

    kali.vm.provider :virtualbox do |v|
      v.memory = 2048
      v.cpus = 2
    end
  end

  config.vm.define "win2k8" do |win2k8|
    win2k8.vm.box = "rapid7/metasploitable3-win2k8"
    win2k8.vm.hostname = 'win2k8'
    win2k8.vm.network :private_network, ip: "172.20.10.8"

    win2k8.vm.provider :virtualbox do |v|
      v.memory = 2048
      v.cpus = 2
    end
  end

  config.vm.define "ub1404" do |ub1404|
    ub1404.vm.box = "rapid7/metasploitable3-ub1404"
    ub1404.vm.hostname = 'ub1404'
    ub1404.vm.network :private_network, ip: "172.20.10.14"

    ub1404.vm.provider :virtualbox do |v|
      v.memory = 2048
      v.cpus = 2
    end
  end

  config.vm.define "primer" do |primer|
    primer.vm.box = "Sliim/vulnhub-primer"
    primer.vm.hostname = 'primer'
    primer.vm.network :private_network, ip: "172.20.10.20"

    primer.vm.provider :virtualbox do |v|
      v.memory = 2048
      v.cpus = 2
    end
  end

end