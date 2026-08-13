# Hi, I’m Andreansx 
![https://www.credly.com/badges/3ec4eb66-f917-4889-a253-4104da6ea654/public_url](./ccna_sm.jpg)    

I'm a 17 year old CCNA-certified self-taught focused on internet routing and edge infrastructure, Anycast BGP and Linux-based routing with BIRD. 
My primary focus and career goal is Data Center Network Engineering.   

Networking is what I learn for real, but I also mess around with IDA and Claude Code for reverse engineering of software and research.   

As of now I'm in the process of setting up my own Autonomous System with a PI IPv6 /48 which will be originated from two Points of Presence (Vultr and iFog) with eBGP to upstreams and iBGP down through Wireguard tunnels to my MikroTik CCR2004.   
And also there will be my own Looking Glass (`bird-lg-go`), served on two PoPs, so it will take advantage of anycast BGP. I would also want to set up my own nameservers on those PoPs.    
### Toolkit

<div align=“center”>
 
 
![bird](https://img.shields.io/badge/BIRD_BGP_Anycast-000000?style=for-the-badge)
![docker and clab](https://img.shields.io/badge/docker,CLab-2496ED?style=for-the-badge&logo=docker&logoColor=white&logoSize=auto)
![broadcom](https://img.shields.io/badge/StrataXGS-E31837?style=for-the-badge&logo=broadcom&logoColor=white&logoSize=auto)
![jinja2](https://img.shields.io/badge/jinja2,ansible,netbox-7E0C1B?style=for-the-badge&logo=ansible&logoColor=white&logoSize=auto)
![ceos](https://img.shields.io/badge/cEOS-16325B?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNTI3IiBoZWlnaHQ9IjEwOTkiIHZpZXdCb3g9IjAgMCAxNTI3IDEwOTkiPjx0aXRsZT5BcmlzdGEtbmV0d29ya3MtbG9nby1zdmc8L3RpdGxlPjxwYXRoIGQ9Ik04NzQuMyA2MC44YzUyLjEgODQuOSA2NTIgMTAzMS40IDY1MiAxMDMxLjRoLTIxNS4yTDc2My40IDIxNy41IDUyOC43IDU5Ni4xaDQzMC40TDg0OC4yIDc3Mi40SDQxNy45bC0yMDIuMiAzMjYuNEguNlM2MDcgMTM5LjIgNjUyLjYgNjcuNGM1OC43LTg0LjkgMTYzLTkxLjQgMjIxLjctNi42IiBzdHlsZT0iZmlsbDojZmZmIi8+PC9zdmc+&logoColor=white&logoSize=auto)
![junos](https://img.shields.io/badge/cRPD-84B135?style=for-the-badge&logo=junipernetworks&logoColor=white&logoSize=auto)


</div>

I now run Arista cEOSes and Alpine Linux with BIRD using Containerlab in a ARM64 VM in OrbStack. This setup is unimaginably more efficient than an old Dell R710 and physcial hardware. Though I would like to get back to my dell s4048-on with os10 sometime.   

Currently my projects and learning interests include:

*   Bringing up my own AS which is a RIPE-provided PI IPv6 /48 anycasted from two PoPs (Vultr and OCI VPS through BGPTunnel) with full iBGP mesh through wireguard tunnels.   
*   BIRD routing and architecture, I'm learning to write filters and also setting up BGP sessions between contenerized routers. You can take a look [here](https://github.com/Andreansx/Networking-lab/tree/main/projects/27-ibgp-bird-cEOS-wireguard), this is a demo or a PoC for my AS setup.
*   Routing security, RPKI ROAs, IRR route6 objects, filtering AS_PATH and prefix and MANRS-aligned policy
*   Labbing with Linux, cEOS and cRPD containers in Containerlab.   
*   Network automation with Jinja2 and Ansible and a bit with Nornir   


Click the card below to browse all my documentation.  

[![Readme Card](https://github-stats-extended.vercel.app/api/pin/?username=Andreansx&repo=networking-lab&bg_color=191921&hide_border=true&text_color=8D4040&title_color=CE653B&icon_color=AD533E&border_radius=10)](https://github.com/andreansx/networking-lab)  

### Reverse engineering & systems so like side projects with Claude. This is just for fun

Running an i386 Heidenhain TNC640 Vbox appliance under FEXemu on Apple Silicon, cause emulating a Win11 PC on ARM64 is too power-hungry:

[![Readme Card](https://github-stats-extended.vercel.app/api/pin/?username=Andreansx&repo=TNC640unix&bg_color=191921&hide_border=true&text_color=8D4040&title_color=CE653B&icon_color=AD533E&border_radius=10)](https://github.com/andreansx/TNC640unix)    

ARM64 Apple Silicon & Metal port of the game Casualties: Unknown (up to 7.0 demo)

[![Readme Card](https://github-stats-extended.vercel.app/api/pin/?username=Andreansx&repo=casualties-unknown-apple-silicon&bg_color=191921&hide_border=true&text_color=8D4040&title_color=CE653C&icon_color=AD533E&border_radius=10)](https://github.com/andreansx/casualties-unknown-apple-silicon)    


### Contact

<div align="center">

_Always open to chat with fellow BGP, networking, UNIX and Apple enthusiasts!_  
</br>
[![Signal](https://img.shields.io/badge/signal-3B45FD?style=for-the-badge&logo=signal&logoColor=ffffff&logoSize=auto)](https://signal.me/#eu/0ld29h9x9wk_GZgDofNOidDA-QP2Wy9b6CQCriJDe3v6pP_XbpxEgpxBYtEuBS2b)
[![Telegram](https://img.shields.io/badge/telegram-2B59FF?style=for-the-badge&logo=telegram&logoColor=ffffff&logoSize=auto)](https://t.me/Andrtexh)

</div>

