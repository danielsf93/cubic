apt update
sudo snap install –classic anbox-installer && anbox-installer
sudo apt install ./steam_latest.deb 
apt update
sudo apt-add-repository ppa:cubic-wizard/release
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 6494C6D6997C215E
sudo apt-get update
sudo apt-get install cubic
