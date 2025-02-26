# ML_Project
## It's an End to End Machine learning Project.

#### Initial Setup
To create env:
conda create -p venv python==3.10 -y
conda activate venv\
pip install -r requirements.txt
python app.py

#### Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
