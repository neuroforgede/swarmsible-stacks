# swarmsible-stacks
Set of default production grade stacks for use with https://github.com/neuroforgede/swarmsible and https://github.com/neuroforgede/swarmsible-hetzner

This repository is designed to be used in in a setup with an external Load Balancer that handles the routing
to the actual Traefik Ingress via a private Network.

This repository assumes usage of Hetzner for Cloud Volumes via https://github.com/costela/docker-volume-hetzner.

# Used Software

1. docker-stack-deploy for secret rotation (https://github.com/neuroforgede/docker-stack-deploy)