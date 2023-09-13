---
title: "Servers"
permalink: /servers/
excerpt: "Using our own infrastructure ensures we are masters of our own fate."
modified: 2017-01-14T10:05:00-05:00
categories:
  - Servers
tags:
  - Servers
  - Pragmatic
---

The Apache Infrastructure team provides basic maintenance of all hardware and cloud resources in the core ASF infrastructure. Note that we rely on a large network of mirror operators and other CDNs to serve actual downloads of official releases, which are quite large.

Master code repositories and specific other data like mailing lists must be hosted on officially supported Apache infrastructure, to ensure that the ASF is a master of its own fate.  Other less critical services may be run on outside provider services, as long as the ASF can provide oversight, have full data access, and can provide backups in case the outside provider disappears.

Having full control over our projects' data ensures the ASF can continue to operate even in the face of service providers who go out of business, or who otherwise attempt to exert control over ASF operations.  For example, the ASF spends infra resources maintaining our own private git mirror of all ASF repositories.  Controlling the source of truth for our software history gives us several advantages:

- Source code history is securely kept in services we have full control over for security.
- Projects can continue to operate even if GitHub goes down, or is inaccessible in their region.
- Contributors who may have specific legal issues with using GitHub can still contribute directly to our git repos.
- If GitHub terms of service ever change, the ASF could continue to operate purely independently of their service.

While this costs us some effort to maintain and secure, it ensures the ASF can always provide a truly vendor neutral home for all of our projects, without fear of market or ecosystem shifts in service fees, terms of service, or onerous licensing changes.
