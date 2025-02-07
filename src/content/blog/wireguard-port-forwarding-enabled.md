---
title: WireGuard Port Forwarding enabled
url: /blog/wireguard-port-forwarding-enabled/
draft: false
authors:
  - Viktor Vecsei
categories:
  - Releases
# Tags are seperated by comma. Ex. Open Source, Security, Subscriptions
tags:
  - Apps
  - Protocols
  - WireGuard
date: 2022-02-16T07:56:15.000Z
# 740px X 740px
thumbnailImage: /images-static/uploads/windows.png
---
After the recent addition of [Multi-Hop for WireGuard][1], we are now introducing port forwarding support for Wireguard. Port forwarding allows incoming connections on a specific port, enabling you to run various services on your device that need to be accessible from the Internet. This feature comes with potential threats, so we suggest reviewing our [brief introduction][2] to port forwarding.

You can enable port forwarding for both WireGuard and OpenVPN by logging in and visiting the [Port Forwarding tab][3] in your client area.

Please note that WireGuard port forwarding will not be activated automatically until you have disconnected all your active sessions at least once. After doing so please wait 10 mins and reconnect using your chosen protocol.

 [1]: /blog/kill-switch-and-wireguard-multi-hop-added-to-ivpn-for-ios/
 [2]: /knowledgebase/general/what-is-port-forwarding/
 [3]: /account/port-forwarding
