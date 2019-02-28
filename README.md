#sigsci-envoy module

This repo contains an example of running the Signal Sciences Agent with Envoy. Docker Compose is used to orchestrate 3 containers: an NGINX web server, an Envoy ingress proxy, and a Signal Sciences Agent sidecar.

Set the Signal Sciences Agent access and secret key pair within docker-compose.yml
