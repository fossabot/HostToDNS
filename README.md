# HostToDNS.rsc
This script can add your local hostnames to DNS

You can run it manually or add to scheduler.

To add script to scheduler:

``/system scheduler
add interval=30m name=HostToDNS on-event="/system script run HostToDNS"``

Tested on 6.5.34
