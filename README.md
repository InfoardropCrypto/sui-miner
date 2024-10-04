# Tutor Sui Miner

<h3> Siapin 1.5-2 sui di wallet buat gasfee </h3>

# Buka : https://github.dev

# Code :

screen -S sui

git clone https://github.com/suidouble/sui_meta_miner.git
cd sui_meta_miner
npm install

# Ubah sui phrase

node mine.js --meta --chain=mainnet --phrase="phrase sui"
node mine.js --fomo --chain=mainnet --phrase="phrase sui"

# atau bisa pakai ini

node mine.js --fomo --meta --chain=mainnet --phrase="phrase sui"

# Kalau error hapus dulu

rm rf sui_meta_miner

curl -s https://deb.nodesource.com/setup_18.x | sudo bash

sudo apt install nodejs -y 

# Done
