# dev-env-setup

1. nvm
> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

2. node using nvm
>node -e "console.log('Running Node.js ' + process.version)

3. cdk
>npm install -g aws-cdk"

4. docker
> sudo yum install -y docker

5. git
>sudo yum install -y git

Fix permission issues: 

start docker engine
sudo systemctl start docker

sudo groupadd docker
sudo usermod -aG docker ${USER}
logout
Test: docker run hello-world

