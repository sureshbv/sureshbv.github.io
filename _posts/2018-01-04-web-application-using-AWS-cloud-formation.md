---
layout: post
date: 2018-01-04
---

## Problem Statement 
Using AWS cloud formation deploy "hello world" web application (just print hello message when user will send the request) inside AWS ECS using Apache Server.

### _Note_

- Use ELB to configure public access to the website
- website should run over 9090 port
- website should be accessible from Quantiphi network only

Mandatory aws service to be used for this deployment

* CFT
* ECS
* ELB
* EC2
* VPC (don't use default vpc, create new VPC)
* Security Groups

## Solution
