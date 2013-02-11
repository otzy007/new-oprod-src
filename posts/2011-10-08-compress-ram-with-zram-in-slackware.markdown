---
layout: post
title: !binary |-
  Q29tcHJlc3MgUkFNIHdpdGggelJhbSBpbiBTbGFja3dhcmU=
joomla_id: 92
joomla_url: !binary |-
  Y29tcHJlc3MtcmFtLXdpdGgtenJhbS1pbi1zbGFja3dhcmU=
date: 2011-10-08 16:14:43.000000000 +03:00
---
<h2><strong>Update: </strong>you can find the tarball for this script at: <a href="http://github.com/downloads/otzy007/enable-zRam-in-Slackware/enable-zram-noarch.tgz">http://github.com/downloads/otzy007/enable-zRam-in-Slackware/enable-zram-noarch.tgz </a></h2>
<p>Referring to this<a href="http://www.webupd8.org/2011/10/increased-performance-in-linux-with.html" target="_blank"> article</a> it seems that using a swap disk is slower than compressing the data in the memory.</p>
<p>Enabling this under Slackware Linux it's pretty easy.</p>
<p> </p>
<p>Create the file /etc/rc.d/rc.zram and put this script into it:</p>
<p> </p>

<script src="http://snipt.net/embed/75ce2bb2d1fb6f7442a71f3861f3a856" type="text/javascript"></script>
<p> </p>
<p><strong>Remember to make it executable:</strong> chmod +x /etc/rc.d/rc.zram</p>
<p> </p>
<p>Also copy this lines to /etc/rc.d/rc.local or /etc/rc.d/rc.M</p>
<p>
<script src="http://snipt.net/embed/59f8882162d8e8e915de48d5336f014c" type="text/javascript"></script>
</p>
