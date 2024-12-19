# composefiles

My Useful Docker Compose files

## How to install Docker Engine on Debian

```bash
sudo apt update
sudo apt upgrade -y
curl -fsSL https://get.docker.com -o get-docker.sh
DRY_RUN=1 sh ./get-docker.sh # check executing commands
DEBIAN_FRONTEND=noninteractive sudo sh get-docker.sh
sudo usermod -aG docker $USER
newgrp docker
```
