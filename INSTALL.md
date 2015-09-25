INSTALL doc written for Ubuntu 14.04 but should work on other platforms.

Ubuntu 14.04

sudo apt-get install python-pip python-dev build-essential
sudo pip install --upgrade pip
sudo pip install --upgrade virtualenv

Install the RYU controller

wget https://raw.githubusercontent.com/sdnds-tw/ryuInstallHelper/master/ryuInstallHelper.sh
sudo bash ryuInstallHelper.sh
sudo easy_install Distribute

Clone the repo
git clone https://github.com/REANNZ/faucet.git

cd faucet
python setup.py install
