# portainer
https://www.incapio.com/post/install-portainer-on-cloud-run-google-cloud-gcp

```
docker pull portainer/portainer-ce
docker tag portainer/portainer-ce gcr.io/<project-id>/portainer-community-edition
docker push gcr.io/<project-id>/portainer-community-edition
```
