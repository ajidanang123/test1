# Command

1. Update Dulu 

apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot



3. Cara Install

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/ajidanang123/test1/main/install/sshonly.sh && chmod +x sshonly.sh && sed -i -e 's/\r$//' sshonly.sh && screen -S sshonly ./sshonly.sh


