sfc-dkms-deb
============

Solarflare DKMS Debian Package

I popped open the Solarflare DKMS RPM, got it up and running on an Ubuntu machine, then built up a .deb with the DKMS commands.

Solarflare URL: https://support.solarflare.com/index.php?view=categories&id=1945&option=com_cognidox&Itemid=2

License: GNU GPLv2

The source code is _inside_ of the package. Use `ar vx sfc-dkms_4.*.deb` to extract the .deb. You'll find a data.tar.gz file, use `tar -tzvf data.tar.gz` to extract data.tar.gz. For more information see http://www.tldp.org/HOWTO/Debian-Binary-Package-Building-HOWTO/x60.html

```
Copyright 2005-2006 Fen Systems Ltd.
Copyright 2006-2013 Solarflare Communications Inc.

LM87:
Copyright (C) 2000       Frodo Looijaard <frodol@dds.nl>
                         Philip Edelbrock <phil@netroedge.com>
                         Stephen Rousset <stephen.rousset@rocketlogix.com>
                         Dan Eaton <dan.eaton@rocketlogix.com>
Copyright (C) 2004-2008  Jean Delvare <khali@linux-fr.org>

LM90:
Copyright (C) 2003-2008  Jean Delvare <khali@linux-fr.org>
```
