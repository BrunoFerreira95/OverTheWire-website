---
layout: default
listwarzone: true
title: How to connect?
---

How to connect?
===============


To get access to the warzone, go to the #warzone channel on our [Discord] and talk
to the Warzone Dispenser bot.  The bot will reply to you with instructions.

You will receive an OpenVPN config file containing all the information you need
to connect to the warzone. On a Linux commandline, you can run the following
command as root to connect to the warzone (assuming you named the received file
"myconfig.ovpn"):

```
openvpn myconfig.ovpn
```

Of course, in order to use OpenVPN on your computer, you will need to install
it first.  Use Google to figure out how to install OpenVPN on your Operating
System.

{% include beginNote.html title="Warning about insecure networks" %}
The warzone is an experimental network without any protection. Your computer
will be exposed to attacks, but not more than on any free wifi accesspoint you
connect to.  Still, it's always a good idea to use adequate protection (e.g.
have a firewall and/or use a virtual machine to connect to the warzone).
{% include endNote.html %}

[Discord]: /information/chat.html
