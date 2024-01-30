# QCA6174-ubuntu-driver
An actually working driver for QCA6174 Wireless Network Adapter. Which is used in Microsoft Surface Go and Redmibook laptops.


# General information
Due to I have been using the Redmibook 16 for a long time. Every time I installed UBUNTU, the internal WiFi card always could not been used. I used to spend many hours each time to solve this problem but I found the best solution for me finally. Which is just install the `surface-go-wifi_0.0.5_amd64.deb` by following these steps:

```bash
git clone https://github.com/geeksloth/QCA6174-ubuntu-driver.git && cd QCA6174-ubuntu-driver
```
```bash
sudo dpkg -i surface-go-wifi_0.0.5_amd64.deb
```
then reboot your computer
```bash
reboot
```
and Hoola! It's working like a charm!


## Info for Nerds
```
description: Wireless interface
product: QCA6174 802.11ac Wireless Network Adapter
vendor: Qualcomm Atheros
logical name: wlp1s0
version: 32
width: 64 bits
clock: 33MHz
capabilities: bus_master cap_list ethernet physical wireless
configuration: broadcast=yes driver=ath10k_pci driverversion=6.5.0-15-generic firmware=WLAN.RM.4.4.1-00157-QCARMSWPZ-1 ip=192.168.1.58 latency=0 link=yes multicast=yes wireless=IEEE 802.11
```
