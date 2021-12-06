Docker image build pipeline

```
Technology 
docker, ubuntu, nginx, jenkins

Put your credential in Jenkins option username and password, 
and copy your credentials ID for pipeline -> shamal317mn-dockerhub

DOCKERHUB_CREDENTIALS = credentials('shamal317mn-dockerhub') 


sh 'docker build -t shamal317mn/simple-webpage  Dockerhub-pushImage/'

use your dockerhub username at beginning of image name like -> shamal317mn
plus specify folder where you Dockerfile -> Dockerhub-pushImage/

```