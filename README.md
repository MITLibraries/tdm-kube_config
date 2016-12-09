
Kubernetes Config for TDM
=========================

This config file will deploy the various components of the kubernetes cluster. The services need to be created before the deployments.

    $ kubectl create -f services
    $ kubectl create -f deployments

Changes to a particular deployment can be deployed with:

    $ kubectl apply -f deployments/pit.yml
