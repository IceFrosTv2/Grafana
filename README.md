# Grafana
apt update 
apt install curl 
git clone https://github.com/IceFrosTv2/Grafana 
wget -O get-docker.sh https://get.docker.com 
sudo sh get-docker.sh 
sudo apt install -y docker-compose 
rm -f get-docker.sh 
docker-compose up -d 
