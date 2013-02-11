---
layout: post
title: !binary |-
  VHVybmluZyBPTi9PRkYgd2lyZWxlc3Mgb24gQVNVUyBLNTJq
joomla_id: 90
joomla_url: !binary |-
  dHVybmluZy1vbm9mZi13aXJlbGVzcy1vbi1hc3VzLWs1Mmo=
date: 2011-03-31 21:31:42.000000000 +03:00
---
<p>Here's a quick fix to enable/disable wireless using Fn+F2 on [[Slackware]] [[Linux]] on ASUS K52j and also the LED to indicate the status of the wireless.</p>
<p>First you need to create this file: /etc/acpi/events/etc/acpi/events/asus-wireless-switch</p>
<p>This file will contain the hotkey and the path to the script which is setting the wireless ON/OFF.</p>
<p>The /etc/acpi/events/etc/acpi/events/asus-wireless-switch content will be:

</p>
<script src="http://snipt.net/embed/09ca39d3491a2e7835be0025c21a9eab" type="text/javascript"></script>

<p>Then create another one: /etc/acpi/asus-wireless-switch.sh</p>

<p>With this script in it:</p>
<script type="text/javascript" src="http://snipt.net/embed/f6fe86eb87f0f53b9660ed24a0ae4c86"></script>
