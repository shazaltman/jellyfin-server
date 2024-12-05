INSTALAÇÃO DO JELLYFIN-SERVER

sudo apt update -y

sudo apt install git -y

git clone https://github.com/shazaltman/jellyfin-server.git

cd jellyfin-server

chmod +x jellyfin

sudo ./jellyfin

docker ps

ip a
