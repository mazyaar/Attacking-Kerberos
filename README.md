# Attacking-Kerberos
This document will cover all of the basics of attacking Kerberos the windows ticket-granting service; we'll cover the following:

* Initial enumeration using tools like Kerbrute and Rubeus
* Kerberoasting
* AS-REP Roasting with Rubeus and Impacket
* Golden/Silver Ticket Attacks
* Pass the Ticket
* Skeleton key attacks using mimikatz

This document will be related to very real-world applications and will most likely not help with any CTFs however it will give you great starting knowledge of how to escalate your privileges to a domain admin by attacking **Kerberos** and allow you to take over and control a network.

It is recommended to have knowledge of general post-exploitation, active directory basics, and windows command line to be successful with this document.

![](https://i.imgur.com/2dq2jLY.png)![1728288300327](image/AttackingKerberos/1728288300327.png)
