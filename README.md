# GNS3-Ubuntu

#Config Ubuntu

sudo sed -i 's/archive.ubuntu.com/mirror.twds.com.tw/g' /etc/apt/sources.list

#Install GNS3 on ubuntu

sudo add-apt-repository ppa:gns3/ppa
sudo apt update                                
sudo apt install gns3-gui gns3-server

