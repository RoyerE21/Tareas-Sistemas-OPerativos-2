pruebas@pruebas-VirtualBox:~$ history
    1  ls
    2  sudo apt update && sudo apt upgrade
    3  ping n -3  google
    4  ping 8.8.8.8
    5  sudo apt update && sudo apt upgrade
    6  sudo apt install ca-certificates curl
    7  sudo install -m 0755 -d /etc/apt/keyrings
    8  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg   -o /etc/apt/keyrings/docker.asc
    9  sudo chmod a+r /etc/apt/keyrings/docker.asc
   10  sudo groupadd docker
   11  whoami
   12  sudo usermod -aG docker pruebas
   13  groups
   14  getent
   15  getent group docker
   16  id
   17  newgrp docker
   18  id
   19  groups
   20  getent group docker
   21  docker --version
   22  sudo apt update
   23  sudo apt install ca-certificates curl
   24  sudo install -m 0755 -d /etc/apt/keyrings
   25  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
   26  sudo chmod a+r /etc/apt/keyrings/docker.asc
   27  sudo tee /etc/apt/sources.list.d/docker.sources <<EOF
   28  Types: deb
   29  URIs: https://download.docker.com/linux/ubuntu
   30  Suites: $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}")
   31  Components: stable
   32  Architectures: $(dpkg --print-architecture)
   33  Signed-By: /etc/apt/keyrings/docker.asc
   34  EOF
   35  sudo apt update
   36  sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   37  sudo systemctl status docker
   38  sudo docker run hello-world
   39  id
   40  groups
   41  docker --version
   42  id
   43  groups
   44  sudo reboot
   45  systemd-inhibit --list
   46  id
   47  sudo docker run hello-world
   48  docker run hello-world
   49  docker ps
   50  id
   51  getent groups docker
   52  getent group docker
   53  group
   54  groups
   55  cd Descargas/
   56  ls
   57  less grafana.zip 
   58  unzip grafana.zip 
   59  ls
   60  rm -r grafana
   61  ls
   62  ..
   63  cd ..
   64  ls
   65  /home
   66  cd /home
   67  ls
   68  cd pruebas/
   69  ls
   70  unzip grafana.zip 
   71  ls
   72  rm grafana.zip 
   73  ls
   74  cd grafana/
   75  ls
   76  cd proyecto/
   77  LS
   78  ls
   79  nano docker-compose.yml 
   80  clear
   81  docker compose up -d
   82  docker ps
   83  netstat -tunap
   84  sudo apt install net-tools
   85  netstat -tunap
   86  ip a
   87  sudo apt install mariadb-client
   88  ls
   89  nano docker-compose.yml 
   90  nano haproxy/
   91  cd haproxy/
   92  ls
   93  nano haproxy.cfg 
   94  cd ..
   95  ls
   96  nanao init-db.sql 
   97  nano init-db.sql 
   98  cd web1/
   99  ls
  100  nano Dockerfile 
  101  nano index.php 
  102  cd ..
  103  ls
  104  cd web2/
  105  ls
  106  nano Dockerfile 
  107  nano index.php 
  108  docker ps
  109  history
  110  cd .. 
  111  cd
  112  history
pruebas@pruebas-VirtualBox:~$ 
