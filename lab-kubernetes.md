---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Lab - Kubernetes
description: Now for the best part - playing round with Kubernetes!

# Author box
author:
    title: About Author
    title_url: '#'
    external_url: true
    description: Facundo is a Cloud Solutions Architect at New Signature. He enjoys helping clients with architecture, containers/orchestration, and stream lining development processes.

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Intro to Docker
        url: '/lab-docker'
    next:
        content: Azure DevOps Lab
        url: '/lab-azure-devops'
---

## Overview

Now that you under the value of conterization, how does Kubernetes come into play? 

It's important that you understand the value of Kubernetes, otherwise, it's going to be difficult to understand the _return on the investment_.

### Why Kubernetes?

Here's a quick recap:

- Orchestrate multiple instances of a container across a _pool of resources_.
- Zero-downtime deployments
- Self-healing applications
- [Bin-packing](https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/)

## Mini-Lab - Deployments using Kubernetes

Go to [this KataCoda lab](https://www.katacoda.com/courses/docker/create-nginx-static-web-server​) and follow the instructions.

### Stretch Goals

#### How do you deploy 10 instances of a pod?

Try to modify the Kubernetes deployment so that you deploy 10 instances of a pod.

#### How do you check the status of a deployment?

What `kubectl` command can you run to check the status of a deployment? Try it out.

## Parking Lot

Don't forget, we'll have a parking lot session at the end of the day. 
Let us know what you'd like to add to our list.