---
title: Most Effective Five Dollar Upgrade Ever
author: Damien
layout: post
permalink: /2006/11/most-effective-five-dollar-upgrade-ever/
categories:
  - Tips
---
I finally got around to replacing the broken IDE cable in my computer last night. It had been limping along with an old UDMA33 cable, and now has a proper UDMA100 cable.

**Before:**

<pre>damo@omad:~$ sudo hdparm -t /dev/hdc /dev/hdd
/dev/hdc:  Timing buffered disk reads:   86 MB in  3.07 seconds =  28.05 MB/sec
/dev/hdd:  Timing buffered disk reads:   86 MB in  3.06 seconds =  28.14 MB/sec
</pre>

**After:**

<pre>damo@omad:~$ sudo hdparm -t /dev/hdc /dev/hdd
/dev/hdc: Timing buffered disk reads:  172 MB in  3.01 seconds =  57.15 MB/sec
/dev/hdd: Timing buffered disk reads:  170 MB in  3.02 seconds =  56.23 MB/sec
</pre>

Now my media drives are running approximately twice as fast. I should have done it months ago!