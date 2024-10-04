# Simple python web server for OpenShift tests

## Web server was created based on
Based on 
https://medium.com/oracledevs/create-a-simple-docker-container-with-a-python-web-server-26534205061a
podman build -f Dockerfile . -t web-server-test
podman run -p 8000:8000/tcp web-server-test


## Tekton pipeline and triggers config in OpenShift

Tekton pipeline and triggers config is in folder triggers/.
These config was successfully tested in OpenShift.

The tekton pipeline was created based on following greate tutorial:   
https://github.com/openshift/pipelines-tutorial
