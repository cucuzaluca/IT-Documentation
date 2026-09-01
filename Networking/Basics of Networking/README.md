
## NBN

NBN = National Broadband Network. It's the access network infrastructure that connects many Australian homes and businesses toward their internet provider. It's the physical networking equipment and cabling used to carry your connection from your premises toward the ISP

Depending on the type of NBN connection, this can include things like:

- Fibre-optic cables
- Copper phone lines
- Coaxial cables
- Wireless towers
- NBN connection boxes / NTDs
- Street cabinets/nodes
- Fibre distribution equipment
- NBN's larger network equipment

## SSH
SSH (Secure Shell) is a protocol used for secure remote command-line access, but it can also provide secure file transfers and network tunnelling.
## DNS
DNS = Domain Name System, it translates domain names into IP addresses. Think of DNS as the contacts list of the internet

Humans are good at remembering:
- google.com
- youtube.com
- phasethree.net.au

But computers need an IP address to know where to send network traffic

So, DNS essentially does:
google.com
    ↓
    DNS lookup
    ↓
142.xxx.xxx.xxx

## DNS Servers
Computers will have one or more DNS servers configured. Often, your router or DHCP configuration gives your computer the DNS settings automatically.

You might use DNS servers operated by:
- Your ISP
- Your company
- Google
- Cloudflare
- Your own internal network

For example, Google's public DNS includes 8.8.8.8. So if your PC is configured to use Google Public DNS at 8.8.8.8, your PC can ask Google's DNS resolver: "Hey, what's the IP address for example.com?" and the DNS system finds the answer.
