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
and Hoola! It's work like a charm!
