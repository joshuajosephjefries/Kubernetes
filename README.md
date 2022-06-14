# Kubernetes
# This repository contains the k8 manifest files and other configuration files that are used to run K8s

STATELESS APPLICATION (kind: Deployment)
<br> A stateless application is one that does not care which network it is using, and it does not need permanent storage. Examples of stateless apps may include web servers (Apache, Nginx, or Tomcat).

STATEFUL SET APPLICATION (kind: StatefulSet)
<br> StatefulSet maintains a sticky identity for each of their Pods. The advantages of statefulset are
<ul>
   <li> Stable, unique network identifiers.
   <li> Stable, persistent storage.
   <li> Ordered, graceful deployment and scaling.
   <li> Ordered, automated rolling updates.
</ul>
