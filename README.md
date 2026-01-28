Pull via ansible-pull
----------------------

sudo apt update
sudo apt install git ansible
sudo ansible-pull -U https://github.com/<ditt-repo>/<din-playbook>.git site.yml
