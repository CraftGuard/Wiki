# Protect a BungeeCord Server
To protect your server create an SRV Record. We are using Cloudflare in this case.
<br>
# DNS Configuration
![protect](https://cdn.discordapp.com/attachments/796425544296038400/797913218960982026/unknown.png)
<br>
Now we have configured your DNS. We aren't finished yet however.
<br>
# BungeeCord Configuration
Now we need to go to your bungeecord config.yml and enable the `proxy_protocol: true` option. <br> Once it is enabled all IPS will be forwarded to the mainserver. <br> **Make sure to let us know at support that you are using BungeeCord or else you wont be able to connect to your server!**
![proxyprotocol](https://media.discordapp.net/attachments/796425544296038400/797921964793528340/unknown.png)
