---
description: >-
  Real-life, full-stack, in-depth walkthrough and guide to deploying elixir
  applications. Without avoiding any of the messy bits.
---

# Deploying Phoenix / Elixir Applications

### The Release \|&gt; Containers & Management \|&gt; To The Clouds \|&gt; Instrumentation

This project aims to be an open-source, collaborative, complete-as-possible guide that takes the reader from happily coding away locally on an Elixir application to having a production-grade remote software application. The approach will be to provide in depth walkthrough's of each step needed to reach the promised land. 

Because there are virtually limitless combinations of tools available to achieve a deployment today, the guide attempts to side-car broader strategic, tactical, and technical explanations of each step so that developers can internalize various principles and apply them to their toolchain of choice.

This guide is broken up into major parts.

[Part 1, The Release: Distillery](https://joeyrosztoczy.gitbook.io/elixir-deployment/~/edit/drafts/-LHVQf2YuJaLQz3ZB6or/) walks through building a release - a self-contained description of the applications an Elixir project needs to run, and instructions on how to run them. This includes configuration and booting of the Erlang VM. Once you have a release, you have a best in class capability to put your application on another machine.

Parts 2 and 3, [Containerizing with Docker](https://joeyrosztoczy.gitbook.io/elixir-deployment/~/edit/drafts/-LHVQf2YuJaLQz3ZB6or/), and [Container Management with Kubernetes](https://joeyrosztoczy.gitbook.io/elixir-deployment/~/edit/drafts/-LHVQf2YuJaLQz3ZB6or/) take us to the next level. Part 2 demonstrates how to provide sustainable, ergonomic builds of our application with containers. Part 3 shows how to use container management systems to give superpowers to non-Elixir or Erlang solutions needed in our broader application deployment. 

Part 4, [Remote Machines with AWS](https://joeyrosztoczy.gitbook.io/elixir-deployment/~/edit/drafts/-LHVQf2YuJaLQz3ZB6or/) looks into key AWS building blocks such as EC2, ELB's, Route 53, and RDS to allow us to run on hardware in the cloud.

Finally, Part 5, Advanced Instrumentation, will look at powerful modern tools that allow us to assess the health of our cloud deployment including logging strategies, Erlang tools such as [Observer](http://erlang.org/doc/man/observer.html), database migrations, and code hot-swapping.

