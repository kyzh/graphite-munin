What
====
The akwardly (re)named "graphite-munin" is the papper around Adam Jacob's "Munin-Node to Graphite bridge" candy  
Basicaly, I just added an init script.


Requirement
===========
Your ```/etc/munin/munin-node.conf``` must contain
```
allow ^127\.0\.0\.1$
port 4949
```
Install
=======
```
git clone 
```

Configuration
=============
Replace ```localhost``` by you graphite instance in both the init script and the ruby one.
Replace it only at the top of the init script ```graphitehost=```.
Replace it only in the ```carbon``` class for the  ruby script.
