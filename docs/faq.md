---
layout: default
title: "FAQ"
nav_order: 3
---

# Frequently Asked Questions

## Where is the latest BOM (Bill of Materials)?

The latest BOM can be [found on GitHub in the BOM folder](https://github.com/Positron3D/Prusawire/tree/main/BOM).

## How can I get a Serial # for my finished build?

We are accepting serials over on the [Positron 3D Discord](https://discord.com/invite/positron). Please submit your request to the `#prusawire-serial-request` channel over there.  There is an example submission and numerous other builds to reference for the format.

## Where can I get help with my build?

The community over on the [Positron 3D Discord](https://discord.com/invite/positron) is very helpful.  Check out the `#prusawire-questions` channel there.

## My NiteHawk-SB loses connection when there is a restart

```
Alright, found my way to their "usb and canbus toolboards" there, and they seem to recommend the same fix for the "nitehawk does not reconnect after firmware restart" issue too.
I definitely have the 1.5 board
So, I had to remove both R7 and R6
Now it works.
Flashing works, firmware restart works.

-einarjh PW.0012
```