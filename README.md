# K8s manifests

A collection of K8s manifests to deploy common applications.

Those manifests are meant to deploy the bare minimum for applications to run according to expections.
As such, on top of deployments, manifests include NodePort services (No ingresses) as well as PVCs if the application requires persistent storage.
