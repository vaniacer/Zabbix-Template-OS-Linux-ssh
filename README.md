# Zabbix-Template-OS-Linux-ssh

Zabbix template based on default template <i>'Template OS Linux'</i> but all items(including discovery) changed to <b>ssh agent</b>.
Required Zabbix 4.0+

Once I faced the case when all client's ports were closed except ssh. So I've made this template to monitor client's servers through ssh only.
But it could be resource(cpu) hungry due to a large amount of ssh connections, use with caution, disable all that is not needed.

More about zabbix SSH checks <a href="https://www.zabbix.com/documentation/4.0/manual/config/items/itemtypes/ssh_checks">here</a>

<a href="https://t.me/sshtobash"><img src="https://telegram.org/img/website_icon.svg" width="21"></a>
[![Twitter Follow](https://img.shields.io/twitter/follow/Vaniacer?style=social)](https://twitter.com/Vaniacer)
[![paypal](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/sshto?locale.x=en_US) <sup>Don't hold yourself, buy me a beer)</sup>
