# Kubernetes Attack & Defence: Privilege escalation through Kubelet TLS bootstrapping in GKE
This repository contains all the content related to the talk `Kubernetes Attack & Defence: Privilege escalation through Kubelet TLS bootstrapping in GKE` presented at *Google Developer Group (GDG)*.

### Contact Info
Author: Mohamed (Med) Mouine

Email: [mohamed.mouine.2@ulaval.ca](mailto:mohamed.mouine.2@ulaval.ca)

LinkedIn: [https://www.linkedin.com/in/medmouine/](https://www.linkedin.com/in/medmouine/)

Twitter: [https://twitter.com/yoyoman42_](https://twitter.com/yoyoman42_)

Github: [https://github.com/medmouine](https://github.com/medmouine)

## Talk Details
#### Date: 25th of November 2021
### Title: _**Kubernetes Attack & Defence: Privilege escalation through Kubelet TLS bootstrapping in GKE**_
### Summary:
> Privilege escalation through Kubelet TLS bootstrapping is a well known and documented exploit in the Kubernetes and Google Kubernetes Engine environments. We will start by introducing common exploits and vulnerabilities present in modern Kubernetes clusters and ecosystems. We will then dive deeper into the Kubelet TLS bootstrapping exploit, describe some attack vectors, scenarios, and walk through the exploit steps. We will also evaluate the impact and scope of said exploit and finally visit some of the defence and mitigation approaches to this attack.

## Slides

Slides are rendered through Deckset using the theme `Letter from Sweden`. Markdown code can be inspected in [slides.md](./slides.md).


Rendered PDF version can be seen at [slides.pdf](./slides.pdf)

## Code
Example targets for exploit scenarios can be seen in the [targets folder](./targets). Run `kubectl apply -f ./targets` to deploy.

## Resources
https://github.com/FairwindsOps/rbac-lookup

https://cloud.google.com/kubernetes-engine/docs/concepts/control-plane-security

Important: https://unofficial-kubernetes.readthedocs.io/en/latest/admin/authorization/rbac/#privilege-escalation-prevention-and-bootstrapping

https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/

https://cloud.google.com/kubernetes-engine/docs/concepts/kubernetes-engine-overview

https://kubernetes.io/docs/home/
