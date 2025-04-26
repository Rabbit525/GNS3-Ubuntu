# GNS3-Ubuntu

#Config Ubuntu

sudo sed -i 's/archive.ubuntu.com/mirror.twds.com.tw/g' /etc/apt/sources.list

#Install GNS3 on ubuntu

sudo add-apt-repository ppa:gns3/ppa
sudo apt update                                
sudo apt install gns3-gui gns3-server

#Install Package
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

#Import the official Docker GPG key:
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

#Add the appropriate repo:
sudo add-apt-repository \
"deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) stable"

#Install Docker-CE:
sudo apt update
sudo apt install docker-ce



