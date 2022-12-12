# Common
- `iperf3`
- `luci-app-ttyd`
- `luci-app-wol`
- `luci-ssl-nginx`
- `qemu-x86_64-softmmu` **important for Proxmox** without this packages, the network performance will be poor.

# Hardware Support
- `kmod-igc` Intel i225 support (should be included by default in `22.03`)

# DoH
- `luci-app-https-dns-proxy`

# DoT
- `luci-app-unbound`

# QoS
- `luci-app-sqm`

# VPN
- `luci-app-openvpn`
- `luci-app-wireguard`
- `tailscale`

# Monitoring
- `netdata`
- `luci-app-statistics`
## Prometheus
- `prometheus-node-exporter-lua`
- `prometheus-node-exporter-lua-nat_traffic`
- `prometheus-node-exporter-lua-netstat`
- `prometheus-node-exporter-lua-openwrt`
- `prometheus-node-exporter-lua-wifi` If WiFi is built in
- `prometheus-node-exporter-lua-wifi_stations` If WiFi is built in

# AD blocking
- `luci-app-simple-adblock`
## simple-adblock dependencies
- `curl`
- `dnsmasq-full`
- `ipset`
- `libnetfilter-conntrack3`
- `libnettle8` 

## simple-adblock optional dependencies for faster block-list processing
https://docs.openwrt.melmac.net/simple-adblock/
- `coreutils-sort`
- `gawk`
- `grep`
- `sed` 

# File Transfer
- `rclone`
- `rclone-config`
