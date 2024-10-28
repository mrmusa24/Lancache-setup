# Lancache-setup


 sudo apt update



sudo apt install apt-transport-https ca-certificates curl software-properties-common



curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -



sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"



sudo apt update



sudo apt install docker-ce docker-ce-cli containerd.io



sudo docker run hello-world



 $ git clone https://github.com/lancachenet/docker-compose lancache



~ $ cd lancache



~/lancache $ nano .env



~/lancache $ sudo docker-compose up -d



# => Configure your router to se

rve ONLY lancache-dns
