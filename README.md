sudo apt update
sudo apt install -y curl

curl -fL -o owl-file-manager-0.1.0-source.tar.gz \
  https://github.com/marcusbritanicus/NewBreeze/releases/download/<tag>/owl-file-manager-0.1.0-source.tar.gz

tar -xzf owl-file-manager-0.1.0-source.tar.gz
cd owl-file-manager-0.1.0
sh packaging/install-pi-arm64.sh
