---
title: IVPN for iOS - Open-source VPN app for your iPhone and iPad
description: The IVPN app for iOS is designed for iPhone and iPad and offers you comprehensive privacy leak protection, automatic connection on insecure Wi-Fi and Multi-hop.
h1: IVPN for iOS
subtitle: Fully supports both iPhone and iPad (iOS 12.0+)
url: /apps-ios/
platform: ios
layout: apps
image: apps/ios-app
releases: [{
    cta: Get it on App Store,
    download: "https://apps.apple.com/us/app/ivpn-serious-privacy-protection/id1193122683?mt=8",
    github: https://github.com/ivpn/ios-app,
    changelog: https://github.com/ivpn/ios-app/blob/master/CHANGELOG.md
}]
---
## Features

- WireGuard, OpenVPN or IPSec protocols.
- WireGuard privacy controls - Define automatic key and IP address rotation schedule.
- AntiTracker that blocks ads, adware, malicious websites and data harvesting trackers.
- Ability to define trusted Wi-Fi networks and create rules for automatic VPN connection/disconnection
- Multi-hop VPN routes. Connect through multiple servers in separate jurisdictions for enhanced privacy.
- Port forwarding for OpenVPN, reserved on all servers.
- Supports defining custom DNS servers with custom DoH/DoT URL.

## Manual configuration

If you prefer not to use the IVPN app please follow the relevant setup guide below.

If you are using OpenVPN download the latest OpenVPN [UDP](/releases/config/ivpn-openvpn-config.zip) or [TCP](/releases/config/ivpn-openvpn-config-tcp.zip) configuration files. In most cases, you want to use the UDP Protocol.

- [WireGuard](/setup/ios-wireguard/)
- [OpenVPN Connect](/setup/ios-openvpn-connect/)  
- [IPSec with IKEv2](/setup/ios-ipsec-ikev2/)
