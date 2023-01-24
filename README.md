sudo su

sudo apt update

sudo apt upgrade

apt install python3-pip

pip3 install beautifulsoup4

apt-get install apache2

---------------------------------------------------------------

cd /var/www

rm -rf html

mkdir html

cd html

git clone https://github.com/TsugawaNaoki0/ghost_mail.git

mv ghost_mail/* ./

chmod 666 data/quake_data.txt

while true; do python3 ghost_mail.py "〇〇〇〇〇〇〇〇"; sleep 60s; done
