# Kubernetes 101 Content

In this workshop you will learn how to:

* Deploy and manage Docker containers using kubectl

All of the code for this workshop was written by [Kelsey Hightower](https://twitter.com/kelseyhightower) and adjusted for newer versions by me.

There are also [slides with speaker notes](https://docs.google.com/presentation/d/1n3avmL5GCYCYJEr8pLFBKe0wzvoOiUV2vxyW_pYFL5s/edit?usp=sharing).

## Labs

Kubernetes is all about applications and in this section you will utilize the Kubernetes API to deploy, manage, and upgrade applications. In this part of the workshop you will use an example application called "app" to complete the labs.

* [Containerizing your application](labs/containerizing-your-application.md)
* [Creating and managing pods](labs/creating-and-managing-pods.md)
* [Monitoring and health checks](labs/monitoring-and-health-checks.md)
* [Managing application configurations and secrets](labs/managing-application-configurations-and-secrets.md)
* [Creating and managing services](labs/creating-and-managing-services.md)
* [Creating and managing deployments](labs/creating-and-managing-deployments.md)
* [Rolling out updates](labs/rolling-out-updates.md)

## Lab Docker images

App is an example 12 Factor application. During this workshop you will be working with the following Docker images:

* [askcarter/monolith](https://hub.docker.com/r/askcarter/monolith) - Monolith includes auth and hello services.
* [askcarter/auth](https://hub.docker.com/r/askcarter/auth) - Auth microservice. Generates JWT tokens for authenticated users.
* [askcarter/hello](https://hub.docker.com/r/askcarter/hello) - Hello microservice. Greets authenticated users.
* [nginx](https://hub.docker.com/_/nginx) - Frontend to the auth and hello services.

## Links

  * [Kubernetes](https://www.kubernetes.io)
  * [Kubernetes Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
  * [Microk8s: Working with kubectl](https://microk8s.io/docs/working-with-kubectl)
  * [Docker](https://docs.docker.com)
  * [etcd](https://coreos.com/docs/distributed-configuration/getting-started-with-etcd)
  * [nginx](http://nginx.org)
