# Installing Mariadb Server in Ubuntu 20.04
  ### check at main page of maridadb for mirror etc  https://mariadb.org/

sudo apt-get install software-properties-common dirmngr apt-transport-https

sudo apt-key adv --fetch-keys 'https://mariadb.org/mariadb_release_signing_key.asc'

sudo add-apt-repository 'deb [arch=amd64,arm64,ppc64el] https://mirrors.piconets.webwerks.in/mariadb-mirror/repo/10.5/ubuntu focal main'

sudo apt update

sudo apt install mariadb-server
