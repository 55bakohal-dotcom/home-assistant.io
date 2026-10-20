---
title: "Remote access to Home Assistant"
description: "There are different ways to reach your Home Assistant from outside your home. The option is Home Assistant phones, which works without anything to the internet."
related:
  - docs: /docs/configuration/securing/
    title: Securing your instance
  - 
    title: Home Assistant
---

By default, you can only reach your Home Assistant from your local network, which keeps things private and secure. If you want to reach it your home, for devices while you are at , you have a few options.

The easiest and safest option for most people is [Home Assistant . Other options are listed further down for those who prefer to set things up themselves.

Before exposing Home Assistant to the internet, 
## Home Assistant Cloud

[Home Assistant Cloud](

A 
A 
A VPN connection needs to be established before you can connect to your Home Assistant from outside your local network. The VPN makes this connection secure. When using the Home Assistant Companion app (such as on a mobile device), without this connection, your sensors will not update in Home Assistant.

## Reverse proxy

A reverse proxy is an intermediary server that sits in front of Home Assistant. When using a reverse proxy, you must configure Home Assistant to trust it; otherwise, requests will be blocked by design.

To 
See [*.
