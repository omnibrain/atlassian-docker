FROM hwuethrich/bamboo-server

# install dependencies
RUN apt-get update && apt-get upgrade -y && apt-get install -y make gcc build-essential python-pip

# nodejs 
RUN curl -sL https://deb.nodesource.com/setup_0.12 | sudo bash -
RUN apt-get install -y nodejs

# grunt & bower
RUN npm install -g grunt-cli bower

# Docker (run this image like this):
#docker run -v /var/run/docker.sock:/var/run/docker.sock \
           #-v $(which docker):/bin/docker \
           #-ti this-image

# docker-compose
RUN pip install docker-compose



