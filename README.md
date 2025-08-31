# Hi, I’m andreansx 

I'm a 16 year old self-taught Networking and infrastructure enthusiast and I have a really deep passion for the technologies that power the todays internet.
My primary focus and career goal is Data Center Network Engineering.   

### Toolkit

<div align=“center”>

![arch](https://img.shields.io/badge/arch-2B0948?style=for-the-badge&logo=archlinux&logoSize=auto&logoColor=white)
![terraform](https://img.shields.io/badge/terraform-4C1B45?style=for-the-badge&logo=terraform&logoColor=white&logoSize=auto)
![proxmox](https://img.shields.io/badge/proxmox-6C2E43?style=for-the-badge&logo=proxmox&logoColor=white&logoSize=auto)
![kubernetes](https://img.shields.io/badge/kubernetes-8D4040?style=for-the-badge&logo=kubernetes&logoColor=white&logoSize=auto)
![vsrx](https://img.shields.io/badge/vSRX-AD533E?style=for-the-badge&logo=juniper-networks&logoColor=white&logoSize=auto)
![routeros](https://img.shields.io/badge/routeros-CE653B?style=for-the-badge&logo=mikrotik&logoColor=white&logoSize=auto)

</div>

### Things Im currently Learning

* **vSRX** and **VyOS**
* **BGP** <-- Very cool thing with this. Check out my [case study](https://github.com/Andreansx/Networking-lab/tree/main/projects/12-eBGP-implementation) regarding eBGP implementation as the core of my lab!
* **Calico CNI for Kubernetes**
* **MikroTik RouterOS v7**

Im also studying for the CCNA exam. 
Good thing is that Im not learning from scratch but I need to learn Cisco IOS syntax and Cisco-specific things.  

### My lab for learning

Just a brief overwiew.

Lab is build in a datacenter-grade HPE 36U Rack powered by HPE 0U PDU S1132.  

Core is made of a MikroTik CCR2004-1G-12S+2XS and a CRS326-24S+2Q+RM connected by two parallel eBGP sessions.  
The CRS326 handles inter-vlan routing using its ASIC instead of the CPU thanks to L3HW Offload.  

Im also now learning JunOS using vSRX.

Soon I would like to expand my BGP area with vSRX Router to stop using L2 separation with VLANs between the PVE and CRS326. 
I am also planning to drop inter-VLAN routing for VLANs 30,40,50 etc. and only leave inter-VLAN routing between point-to-point networks between CRS326 SVIs and vSRXs and let all of them learn routes to the VLANs 30,40 etc. with BGP which will be running on all routers.   

CRS326 won't be connected on L2 to the usual VLANs and instead it will route traffic between transit links, which will connect it to the VLANs but only through vSRXs.

This might be the most complicated thing I have ever thought about so Im still learning a lot to be able to do this

Recently I got more into Kubernetes, specifically the Calico CNI as it uses BGP for advertising routes to pods in the cluster.

Key Technologies I learn/use in it: 
* MikroTik RouterOS - inter-VLAN routing, dynamic routing protocols, L3 hardware offloading etc. 
* Proxmox Virtual Environment
* vSRX and VyOS
* IPv6 <— Right now working on a tunnel from Hurricane Electric !
* Linux
* ZFS and XFS
* Server management
* a bit of Terraform, Ansible and Kubernetes
  
Click the Card below to browse through all my documentantion.  

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=andreansx&repo=networking-lab&bg_color=191921&hide_border=true&text_color=8D4040&title_color=CE653B&icon_color=AD533E&border_radius=10)](https://github.com/andreansx/networking-lab)

### Check out my dotfiles !

Here you can take a look into the aesthetic part of my lab. Maybe you will find something you will like here

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=andreansx&repo=dotfiles&bg_color=191921&hide_border=true&text_color=8D4040&title_color=CE653B&icon_color=AD533E&border_radius=10)](https://github.com/andreansx/dotfiles)

### Contact

<div align=“center”>

_Always open to chat with fellow networking and Linux enthusiasts!_  
</br>
[![Telegram](https://img.shields.io/badge/telegram-2B59FF?style=for-the-badge&logo=telegram&logoColor=ffffff&logoSize=auto)](https://t.me/Andrtexh)
[![Apple Music](https://img.shields.io/badge/Apple%20Music-%23FA243C?style=for-the-badge&logo=applemusic&logoSize=auto)](https://music.apple.com/profile/andreansx)

</div>
