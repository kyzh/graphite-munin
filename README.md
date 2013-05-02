What
====
The akwardly named "graphite-munin" is the papper around Adam Jacob's "Munin-Node to Graphite bridge" candy
Basicaly, I just added an init script.


Requirement
===========
Your ```/etc/munin/munin-node.conf``` must contain
```
allow ^127\.0\.0\.1$
port 4949
```
