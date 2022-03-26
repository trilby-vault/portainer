# portainer
https://www.incapio.com/post/install-portainer-on-cloud-run-google-cloud-gcp

Navigate to the container registry in the Google cloud console and open cloud shell access to pull the portainer community editions from the docker. Lastly, push the portainer image to the container registry using the following commands.
```
docker pull portainer/portainer-ce
docker tag portainer/portainer-ce gcr.io/<project-id>/portainer-community-edition
docker push gcr.io/<project-id>/portainer-community-edition
```


Next:

Then, type the service name and choose the region.
Next, specify the CPU allocation, pricing and auto-scaling options. Also, select the "Allow all traffic" option in the ingress and select the "Allow unauthenticated invocations" in the Authentication. 
Lastly, Expand the "Container, Variables & Secrets, Connections, Security" option and type "9000" in the container port under the container tab. 
Finally, click on the "create" option to deploy the portainer. 
