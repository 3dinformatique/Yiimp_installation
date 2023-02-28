1 - Install a fresh Ubuntu server 18
2 - Connect to the server by SSH ->  ssh user@ipadresse
3 - launch theses command lines :
sudo apt update
sudo apt upgrade -y
sudo apt install git
cd && git clone https://github.com/3dinformatique/Yiimp_installation.git
cd Yiimp_installation
chmod +x runinstall_Ubuntu18.sh
bash runinstall_Ubuntu18.sh
