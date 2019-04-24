# pingbox-cli

Showcase of an isolated/portable access point with detachable layers

this goal is achived by sharing a Network Namespace with a master container (busybox), other containers can join master container's network. thus an isolated access point with detachable layers.

this foundation allows you to just setup a DHCP server, or add more layers such as an openvpn or pihole container.

### usage:
```bash
pingbox-cli <start|stop> <interface>

pingbox-cli start wlan0
```

default ssid/password is `pingbox/pingbox12345`