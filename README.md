# firewallsetup
## Download the rules to /etc/
```
git clone https://github.com/dtngit/firewallsetup.git
chmod +x firewall*
./firewall
```
## Arch Linux Distributions
```
sudo iptables-save > /etc/iptables/iptables.rules
or
sudo iptables-save -f /etc/iptables/iptables.rules
```
