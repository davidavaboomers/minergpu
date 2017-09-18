#!/bin/bash
sudo apt-get install -y git
sudo git clone https://github.com/davidavaboomers/minergpu.git
cd $HOME/minergpu/
chmod +x install
./install

SCRIPT_PATH=$(realpath $0)
rm $SCRIPT_PATH 
