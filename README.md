Creates virtual Ethernet networks of almost unlimited size.

# Optional depencies
* miniupnpc
* libnatpmp

# Issues

afther compilation and create package, you probably you can see message

> zerotier-cli: missing port and zerotier-one.port not found in /var/lib/zerotier-one
 
so you must run (as root)

> service zerotier-one start
