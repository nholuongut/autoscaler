# Kubernetes Autoscaler

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This repository contains autoscaling-related components for Kubernetes.

## What's inside

[Cluster Autoscaler](https://github.com/nholuongut/autoscaler/tree/master/cluster-autoscaler) - a component that automatically adjusts the size of a Kubernetes
Cluster so that all pods have a place to run and there are no unneeded nodes. Supports several public cloud providers. Version 1.0 (GA) was released with kubernetes 1.8.

[Vertical Pod Autoscaler](https://github.com/nholuongut/autoscaler/tree/master/vertical-pod-autoscaler) - a set of components that automatically adjust the
amount of CPU and memory requested by pods running in the Kubernetes Cluster. Current state - beta.

[Addon Resizer](https://github.com/nholuongut/autoscaler/tree/master/addon-resizer) - a simplified version of vertical pod autoscaler that modifies
resource requests of a deployment based on the number of nodes in the Kubernetes Cluster. Current state - beta.

[Charts](https://github.com/nholuongut/autoscaler/tree/master/charts) - Supported Helm charts for components above.

## Contact Info

Interested in autoscaling? Want to talk? Have questions, concerns or great ideas?

Please join us on #sig-autoscaling at https://kubernetes.slack.com/, or join one
of our weekly meetings.  See [the Kubernetes Community Repo](https://github.com/kubernetes/community/blob/master/sig-autoscaling/README.md) for more information.

## Getting the Code

Fork the repository in the cloud:
1. Visit https://github.com/nholuongut/autoscaler
1. Click Fork button (top right) to establish a cloud-based fork.

The code must be checked out as a subdirectory of `k8s.io`, and not `github.com`.

```shell
mkdir -p $GOPATH/src/k8s.io
cd $GOPATH/src/k8s.io
# Replace "$YOUR_GITHUB_USERNAME" below with your github username
git clone https://github.com/nholuongut/autoscaler.git
cd autoscaler
```

Please refer to Kubernetes [Github workflow guide] for more details.

[GoDoc]: https://godoc.org/k8s.io/autoscaler
[GoDoc Widget]: https://godoc.org/k8s.io/autoscaler?status.svg

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: Nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* [PayPal.me](https://www.paypal.com/paypalme/nholuongut)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟