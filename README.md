# AutomatedPenetrationTestingTool
The main script is "interface-2.py" .
While installing and running our project, you need to be sudo.
Please Install this requirements first: 

cd AutomatedPenetrationTestingTool
cd GooFuzz
chmod +x GooFuzz
./GooFuzz -h
cd ..
pip3 install -r req.txt
pip install requests
pip install colorama

cd spiderfoot
pip3 install -r requirements.txt
cd ..
sudo apt install sublist3r
cd /usr/share/wordlists
git clone https://github.com/danielmiessler/SecLists
cd -
cd ..
sudo pip install python-nmap
cd /usr/share/nmap/scripts/
git clone https://github.com/vulnersCom/nmap-vulners.git
git clone https://github.com/scipag/vulscan.git
cd vulscan/utilities/updater/
chmod +x updateFiles.sh
./updateFiles.sh
