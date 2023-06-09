<p align="center">
  <img width="100%" src="./assets/home-lab.svg" />
</p>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Introduction: What is a "home lab"?](#introduction-what-is-a-home-lab)
  - [Who is a home lab for?](#who-is-a-home-lab-for)
    - [What hardware should I invest in?](#what-hardware-should-i-invest-in)
- [These are the tools and settings I am using in my home lab.](#these-are-the-tools-and-settings-i-am-using-in-my-home-lab)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Introduction: What is a "home lab"?

A home lab is basically an over-engineered home networking setup for uber nerds. You can self-host your blog and airgap your IoT traffic with a VLAN on your UniFi Dream Machine Pro or SE, but it really isn't necessary.

Most of us who have home labs have (or in my case, had, at least for the moment) disposable income and a desire to learn, break stuff, get angry, and try again. That's the best part about it besides the gear; getting to understand how the internet and networking works by breaking it.

## Who is a home lab for?
For anyone who has the income and the stubborness to learn how these things work. Once you get your lab setup, it is just three levels away from house guests thinking you're a tech genius.

### What hardware should I invest in?

Start *very, very, small*. I've built up the stuff I have over two and a half years, with the beginning of this year picking up used Intel NUCs from eBay to have a Proxmox cluster to administer self-hosting stuff that I am still learning, deploying VMs to tinker with operating systems and pen testing.

Maybe grab a server rack, a cheap one will do. A good, solid router is a must if you're going to be doing this. Pick up a decent ethernet switch and a dedicated mini PC and get your hands dirty. All this can be had for under $500.

You'll find my setup below.
# These are the tools and settings I am using in my home lab.


| Device                                       | Image                         | OS  | Where to Buy |
| -------------------------------------------- | ----------------------------- | --- | ------------ |
| Used NUCs                                    | ![nucs]                       | C1  | D1           |
| Intel NUC                                    | ![ha-nuc]                     | C2  | D2           |
| UniFi Dream Machine Pro                      | ![udm-pro]                    | C3  | D3           |
| UniFi Flex HD AP                             | ![unifi-flex-hd]              | C4  | D4           |
| TP-Link (T1600G-18TS) 16 Port Managed Switch | ![tp-link-T1600G-18TS-switch] | C5  | D5           |
| Echogear Server Rack                         | ![rack]                       | C6  | D6           |
| Generic NUC 1U Rack                          | ![nuc-rack]                   | C7  | D7           |
| Cyberpower power strip 12 outlets            | ![cyberpower-strip-12]        | C8  | D8           |
| Cyberpower power strip 18 outlets            | ![cyberpower-strip-18]        | C9  | D9           |
| Synology 9210+ NAS                           | ![synology-9120]              | C10 | D10          |
| Deco X55 Router                              | ![deco-x55]                   | C11 | D11          |
| Navepoint 12U Closet Rack                    | ![navepoint-12u-closet-rack]  | C12 | D12          |




 [nucs]: assets/used-nuc.png
 [ha-nuc]: assets/nuc.png
 [udm-pro]: assets/udm-pro.png
 [tp-link-T1600G-18TS-switch]: assets/tp-link-switch.png
 [rack]: assets/echogear-15u.png
 [nuc-rack]: assets/nuc-rack.png
 [cyberpower-strip-18]: assets/18-outlet-cyberpower.png
 [cyberpower-strip-12]: assets/12-outlet-cyberpower.png
 [synology-9120]: assets/syno-nas.png
 [unifi-flex-hd]: assets/unifi-flex-hd.png
 [deco-x55]: assets/deco-x55.png
 [navepoint-12u-closet-rack]: assets/navepoint-12u.png