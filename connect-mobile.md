---
layout: default
title: Connect Your Mobile Device Directly to Your Computer
---

You have Expo Go installed on your mobile device, and you just ran `yarn install && yarn start` in
our repository. A QR code pops up in your terminal. What to do now?

Note: Easiest to hardest. Try them in order.

# Option 1: Your devices are connected to the same network

If both of your devices are connected to the same network (`eduroam` is weird with this), it should
*just work*™️. Scan the QR code. If it doesn't connect and the IP address on your phone matches the
one printed out in the terminal (right below the QR code), then move on to the next option.

# Option 2: Mobile device hotspot

Note: we take no responsibility for any data uses or phone plan charges this method incurs.
If you are worried about those, or your phone/plan does not allow you to hotspot, then move on the
next option.

1. Start a hotspot on your phone
1. Connect your laptop to your phone's hotspot
1. Scan the QR code
1. should connect, otherwise move onto next option

# Option 3: Tailscale

[Tailscale](https://tailscale.com/) is a VPN service, but rather than providing a server through
which your traffic is routed, it connects two of your own devices together. It is free to use.

## To establish a VPN connection between your two devices:

1. Create a Tailscale account by clicking "Get Started" on the homepage
1. Install the Tailsale app on both your laptop and mobile device
1. Sign in to the Tailscale app on both devices on the same account

## To route the Expo Go connection through Tailscale

1. Run `yarn start` on your laptop
1. Do not scan the QR code. Instead, note the URL printed below the QR code. For example
   `exp://192.168.0.1:8081`.
1. Replace the IP address in this URL (in the example `192.168.0.1`) with the Tailscale address of
   your device
   1. Go to either Tailscale app and look at the list of devices. They will automatically be named
      after the hostname of the devices, but might modify them slightly (example: replacing spaces
      with underscores, etc.).
   1. You can use this name as a replacement for an IP address. For instance, if your laptop's name
      is `maple`, then the URL would become `exp://maple:8081`.
1. Type this new URL into the browser on your mobile device and then it will redirect you to the
   Expo Go app.
