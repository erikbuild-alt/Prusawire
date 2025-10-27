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

If you are running V1.5 of the LDO Motors NiteHawh-SB USB board (the board that connects to the Raspberry Pi): you need to remove BOTH R6 and R7.

> the issue on NH-SB with a 1.5 USB board that looses communication after a "firmware restart" and needs a power cycle to turn back on is caused by the R7 and R6 resistor. They both need to be removed. There is a guide and video that shows how to remove the R7 here its the same for R6. If you are unable to or damage while trying reach out to your reseller where the kit was purchased and they will send you a replacement.
> @JoseFromLDO on the ![Voron Discord](https://discord.com/channels/460117602945990666/710952853514223617/1417600761436569850)


[PDF Instruction Guide](assets/NiteHawkSB_R6-R7_Resistor_Removal_Guide.pdf): this details for R7, but you will ALSO need to remove R6!

![](images/nitehawbsb_fix.png)