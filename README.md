# docker-image
scan docker image with trivy and push to docker hub

# ensure github actions file
.github/workflows/push-and-scan-docker-image.yml

# Info
every changes on main branch or MR to main branch will trigger actions
will login and push image into Dockerhub
