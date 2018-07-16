---
description: >-
  Beyond build ergonomics: unlocking the potential of container for the entire
  application system.
---

# Container Management: K8s

Containers can play an important role in a vanilla Elixir application deployment. They make building releases straight forward and reproducible, and aid in establishing continuous integration environments.

But container's offer far more potential at the application level where additional technologies are needed to deliver the application's solution. Its exceedingly rare for an application to be purely one technology. 

The application may be exposed to clients via an isolated SPA like React. It may have machine learning or statistics need that require a Python service. Maybe there's a particular piece of the infrastructure that necessitates a system's language like Golang or Rust. The application maybe have evolved from, and still interface with, early web solutions like Rails or PHP.

While the Erlang VM enables an Elixir application to distribute itself and scale, many other technologies need a boost to keep up with that power. Container management systems such as [Kubernetes](https://kubernetes.io/) help deploy, scale, and manage all of these services, independent of the language's ecosystem.

In the Container Management: K8s guide, we'll talk about the benefits and challenges of adopting a container management system. We'll provide a full start-to-finish walkthrough of bootstrapping a Kubernetes system to manage our containers, and we'll set the stage to move our application into the cloud on AWS and implement production grade instrumentation in the cloud.

Section Objectives:

1. [Install Minikube & Kubectl with the official docs](https://kubernetes.io/docs/tutorials/hello-minikube/), enabling local cluster virtualization and management.
2. **NOT\_STARTED** - Creating a **Deployment** pod for our dockerized release.
3. **NOT\_STARTED** - Exposing our deployment to the world with a k8s **Service**.
4. **NOT\_STARTED** - Managing, inspecting, and debugging our clusters.

