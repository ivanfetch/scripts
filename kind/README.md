# Kind Scripts

Ease common tasks running [kind](https://kind.sigs.k8s.io/) - a tool to run local Kubernetes clusters using Docker containers as nodes.

* [kind-ingress](./kind-ingress) - Create a cluster supporting an Ingress controller, and install Ingress Nginx.
* [kind-registry](./kind-registry) - Create a local Docker registry and a kind cluster that uses it. Also provide helper commands to list images and image tags from the registry.
* [kind-ver](./kind-ver) - Create a cluster using a specified version of Kubernetes (1.14+).
