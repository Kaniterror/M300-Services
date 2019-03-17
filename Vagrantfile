Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
  config.vm.define "Active Directory"
  config.vm.box = "opentable/win-2012r2-standard-amd64-nocm"
  config.vm.network "forwarded_port", guest:80, host:8080, auto_correct: true
  vb.memory = "4096"
  config.vm.define "WinClient"
  config.vm.box = "inclusivedesign/windows10-eval"
  config.vm.network "forwarded_port", guest:80, host:8080, auto_correct: true
  vb.memory = "4096"
end
