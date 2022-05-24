<h1 align="center">
SWARM
</h1>

<p><img src="https://raw.githubusercontent.com/tanglebay/swarm-releases/master/logo/swarm_gh_banner.png?sanitize=true"></p>

<p align="center">
SWARM is a script that allows you to easily install and manage an IOTA node. The most important configuration options are given via simple and selectable menu items. About the additional feature "Watchdog", the status of the nodes can be monitored, as well as automatically install updates. A reverse proxy installation is also offered for secure access via HTTPS.
</p>

<p align="center">
    <a href="https://tanglebay.com/swarm" style="text-decoration:none;"><img src="https://img.shields.io/badge/SWARM-Website-9cf.svg?logo=SWARM-Website" alt="SWARM-Website"></a>
    <a href="https://twitter.com/iota_swarm" style="text-decoration:none;"><img src="https://img.shields.io/badge/Twitter-9cf.svg?logo=twitter" alt="Twitter"></a>
    <a href="https://discord.tanglebay.com/" style="text-decoration:none;"><img src="https://img.shields.io/badge/Discord-9cf.svg?logo=discord" alt="Discord"></a>
</p>

---

## Get SWARM
<b>Visit <a href="https://tanglebay.com/swarm">SWARM Website</a></b>

---

## Using SWARM
In the menu of SWARM you navigate with the arrow keys. You confirm an action with the "OK" item or by pressing the Enter key. The "Cancel" item cancels an action or returns to the previous menu.

The configuration of the node should always be done via the configuration point provided by SWARM. It is not advisable to use the advanced configuration, since direct parameters set via this menu item are not taken into account during an update and are therefore reset.

---

## Ports
### Hornet (IOTA)
- Gossip port (peering): 15600/tcp (customizable)
- Autopeering port (peering): 14626/udp (customizable)
- Prometheus: 9311/tcp (if the plugin is activated)
### Hornet (Shimmer)
- Gossip port (peering): 15602/tcp (customizable)
- Autopeering port (peering): 14656/udp (customizable)
### Bee (IOTA)
- Gossip port (peering): 15601/tcp (customizable)
- Autopeering port (peering): 14636/udp (customizable)
### Bee (Shimmer)
- Gossip port (peering): 15603/tcp (customizable)
- Autopeering port (peering): 14676/udp (customizable)
### GoShimmer
- Gossip port (peering): 14666/tcp (customizable)
- Autopeering port (peering): 14646/udp
- Prometheus: 9313/tcp (if the plugin is activated)
### Wasp
- Peering port: 4000/tcp (customizable)
- Nanomsg port: 5550/tcp (customizable)
### Proxy
In the proxy menu you can define a separate domain for each node or one domain for all. Please note that when using a shared domain, a separate port must be defined for each node.
- HTTP: 80/tcp

**Please note that the following ports should not be used for the proxy 8080/tcp-8084/tcp**

---

## Backup SWARM
If you ever want to reinstall your server or SWARM, you can backup your SWARM configuration first.

You can find the configuration files under the following path:
```shell
cd /var/lib/swarm/configs
```

After the reinstallation, simply replace the configurations with your backup, run a SWARM update to update the configuration files (if necessary) and then you can reinstall Hornet and the proxy and have all settings imported directly.

---

## Disclaimer

**Please note that you use this script at your own risk and that I will not be liable for any damages that may occur**

---

## Donate

**IOTA Address:**
```
iota1qr4em93qy2helq9vcxp5hcsnju70ky3pyptc0qnsdz590dzhkatw7sj9h5m
```
