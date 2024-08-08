# Ubuntu VMs Inside of Proxmox

These days, I have figured out that if I need privileged access to a container, an LXC is not the best choice. For instance, if I want to add storage to a container, it is almost impossible to do so with an LXC without making the container a privleged container which comes with security implications that I don't want to manage.

So now I run mission-critical services in Ubuntu VMs on Proxmox. I do not use the tteck's scripts for this; I download an ISO file and upload it to storage on Proxmox and create the VM from scratch.

## Difficult to manage publically shared services

For services I want to share publicly that are a real pita to setup and run on my home server, I use [PikaPods](https://pikapods.com). Yes, it costs money, but I've been running Audiobookshelf for a month now on an initial $5 top up. It's a pittance for such a wonderful service, and each "Pod" has a different price for usage. They don't keep your data and the funds go directly to the open source developers apps you are using.