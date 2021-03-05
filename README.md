# Docker App for Funny Eyes
Based on Funny Eyes - Docker App (2021)

by

thiagodnf.github.io/funny-eyes -> http://thiagodnf.github.io/funny-eyes



## Install Docker on Amazon Linux 2
> sudo yum update -y

> sudo amazon-linux-extras install -y docker

> sudo service docker start

> sudo usermod -a -G docker ec2-user

> sudo systemctl enable docker

> docker info



## Download the code and Build the container
> sudo yum install -y git

> git clone https://github.com/Juli-BCN/cool-eyes-docker.git

> cd cool-eyes-docker

> docker build -t hello-cool .

> docker images