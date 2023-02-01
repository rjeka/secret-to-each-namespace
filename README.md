# Create dockerconfigjson on each Kubernetes namespace

A set of tools with which a secret for the docker registry is created in each Kubernetes namespace.

What tools do you need:  
* [Argocd](https://argo-cd.readthedocs.io)
* [External Secrets operator](https://external-secrets.io/v0.7.2/)
* [kyverno](https://kyverno.io/)

![Diagram](ima/secret-to-each-namespace.drawio.png)