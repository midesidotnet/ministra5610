How to install MINISTRA 5.6.10 or MINISTRA 5.6.9

The Script. The script will download and install Ministra 5.6.9 or Ministra 5.6.10 from either my own hosted source or directly from Ministra's servers.... Yeah that's right :)

wget https://raw.githubusercontent.com/midesidotnet/ministra5610/main/install.sh

Run the Script. 
sudo chmod +X install.sh 

sudo bash install.sh 

During installation, the script will ask for two passwords, 1 for the MySQL root user and the other for a password that Ministra will use to connect to MySQL. You will be asked if you want to download files directly from Ministra's servers. type yes or no, if selecting no the script will download from a mirror. During the last part of the script when sudo phing runs, you will see a message asking you to confirm the authenticity of a source for git, just type yes and press Enter.
login: admin
password: 1
