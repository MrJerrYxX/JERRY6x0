# INSTALL TOOL ON TERMUX >>

apt update && apt upgrade -y
pkg install git
pkg install python
rm -rf JERRY6x0
git clone --depth=1 https://github.com/MrJerrYxX/JERRY6x0.git
cd JERRY6x0
python3 automated.py
