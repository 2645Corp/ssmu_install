# Shadowsocks mu auto installer

This script is applicable to [shadowsocks-py-mu:fsgmhoward](https://github.com/fsgmhoward/shadowsocks-py-mu) version.

## How to use
First make sure that your server os is Debian.

Just clone it and edit ssmu.cfg according to your sspanel and server config.

Then run

`./ssmu_py_install_debian8.sh`

You may need some interact while installation.

## Note
### If you choose to overwrite iptables config in the config file, your iptables config WILL BE OVERWRITTEN!!!
You probably do not need iptables using this version thanks to the internal firewall feature;)
