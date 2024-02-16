# Replit Clone

Backend configuration to run a kubernetes cluster that runs Node.JS applications on each __Pod__.

Uses Ingress as a load balancer to route the requests to the pods.

The Node.JS application receives a Python script and returns the output of the application.

## packages/backend
Runs on each pod through docker containers

## kubernetes-manifests
Kubernetes cluster configuration files
