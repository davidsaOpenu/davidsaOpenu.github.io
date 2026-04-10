---
layout: page
title: swiftacular
description: OpenStack Swift cluster
img:
importance: 3
category: [2024, 2025, 2026]
---

Object storage sits behind a huge share of today's cloud services, from photo backups to data lakes. OpenStack Swift is one of the best-known open-source object stores: a distributed system built for high availability, durability, and concurrency, which stores and retrieves unstructured data through a simple REST API. Understanding how such a system really works means looking at rings and partitions, replication across storage nodes, proxy servers, authentication, and how all of these behave when things go wrong.

Swiftacular makes that exploration practical. It deploys a complete, multi-server Swift cluster on a single host, using Vagrant and libvirt to provision the virtual machines and Ansible to configure them: a package cache, Keystone authentication, SSL termination, a Swift proxy, and three Swift storage nodes, connected by a dedicated replication network. Students work on a realistic distributed storage deployment end to end, from automation and configuration to testing and monitoring.

HW/SW requirements: 6 vCPUs, 24-64 GB RAM, 120-500 GB disk (SSD preferred), Linux (on a baremetal machine)

Language: Python (high), Ansible (high), Shell (basic)

Code repository: [here](https://github.com/davidsaOpenu/swiftacular)

OpenStack Swift book: [here](https://homepages.dcc.ufmg.br/~guimaluf/OpenStack%20Swift.pdf)

Swift wiki: [here](https://wiki.openstack.org/wiki/Swift)

Project management board: [here](https://trello.com/b/eMxey6Rr/osw-evssim-and-swiftacular)
