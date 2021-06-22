Vagrant.configure('2') do |config|

  config.vm.box = "ubuntu/focal64"

  config.vm.provision :shell, inline: <<-EOF
    apt update
    apt install nodejs awscli npm
    npm -g install typescript aws-cdk
  EOF
end
