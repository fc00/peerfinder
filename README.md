# Peerfinder

```sh
> peerfinder geoip 20km
Peering exchange: peering.libp2p.io
Our location: Rungestrasse 20, Berlin, Germany, Europe
Result: 2 peers within 20km
/ip4/1.2.3.4/udp/4737
/ip6/2001:12f8::183/udp/4737

> peerfinder bgp
Peering exchange: peering.libp2p.io
Our network: AS44194, Foerderverein Freie Netzwerke e.V.
Result: 3 peers within AS44194
...

> peerfinder bgp 1
Peering exchange: peering.libp2p.io
Our network: AS44194, Foerderverein Freie Netzwerke e.V.
Result: 14 peers within AS44194 and 1 degree of its neighbours
...

> peerfinder geoip 20km -q | multiaddr filter /ip4/udp
/ip4/1.2.3.4/udp/4737
```
