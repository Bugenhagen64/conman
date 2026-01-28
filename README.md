Pull via ansible-pull
----------------------

sudo apt update
sudo apt install git ansible
sudo ansible-pull -U git@github.com:Bugenhagen64/conman.git site.yml
