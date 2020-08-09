**Configure ZyXel modem in bridged mode**

Login to your ZyXel modem.

Disable wifi, dhcp and the firewall.

Get the **MAC address** of **VDSL_via_Online_nl** from the connection page.

Go to **Network setting > Broadband**.

Edit the line **VDSL_via_Online_nl**.

Change **Mode** from **Route** to **Bridge**.

Leave the **Vlan** setings as is.

Configure your own router on WAN DHCP and change the MAC address of your routers WAN interface to the MAC address from your ZyXel modem.

Restart your ZyXel modem and your own router and everything will work right away.
