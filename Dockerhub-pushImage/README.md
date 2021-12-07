Docker image build pipeline

```
Technology 
docker, ubuntu, nginx, jenkins

Put your credential in Jenkins and select option username and password, 
and copy your credential ID for pipeline -> example shamal317mn-dockerhub
look in below line and in pipeline

DOCKERHUB_CREDENTIALS = credentials('shamal317mn-dockerhub') 


sh 'docker build -t shamal317mn/simple-webpage  Dockerhub-pushImage/'

use your dockerhub username at beginning of image name like -> shamal317mn
plus specify folder where you Dockerfile in Jenkinsfile -> Dockerhub-pushImage/

```