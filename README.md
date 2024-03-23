# Multicloud Gitops

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[Live build status](https://validatedpatterns.io/ci/?pattern=mcgitops)

## Start Here

If you've followed a link to this repository, but are not really sure what it contains
or how to use it, head over to [Multicloud GitOps](http://hybrid-cloud-patterns.io/multicloud-gitops/)
for additional context and installation instructions


# Home assistant repos / notes
https://www.reddit.com/r/homeassistant/comments/ygmcpg/anyone_running_it_in_kubernetes_and_if_yes_how/

https://github.com/cook1emr/dhcp-daemonset/tree/master/multus-dhcp

https://github.com/theautomation/home-assistant/blob/main/deploy/k8s/manifest.yaml

https://github.com/abalage/home-assistant-k8s/blob/main/base/ingress.yml

https://github.com/mortylabs/kubernetes/blob/main/pv_nfs/deployment.yaml

https://github.com/mysticrenji/home-assistant-on-kubernetes

https://github.com/abalage/home-assistant-k8s


#


oc patch consoles.operator.openshift.io cluster  --type=merge \
--patch '{ "spec": { "plugins": ["logging-view-plugin", "gitops-plugin", "kubevirt-plugin", "monitoring-plugin", "nmstate-console-plugin"]}}'


