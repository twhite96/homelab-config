<p align="center">
  <img width="100%" src="./assets/labs.svg" />
</p>


<p align="center">
  <img alt="GitHub Release" src="https://img.shields.io/github/v/release/twhite96/homelab-config?include_prereleases&style=for-the-badge&logo=github&logoColor=black&labelColor=white&color=%23ff0000">
  <img alt="Mastodon Follow" src="https://img.shields.io/mastodon/follow/109435346803331556?domain=https%3A%2F%2Ffosstodon.org&style=for-the-badge&logo=mastodon&logoColor=%23ff0000&label=Fosstodon%20Follows&labelColor=white&color=%23ff0000">
  <img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/twhite96?style=for-the-badge&logoColor=%23ff0000&labelColor=white&color=%23ff0000">
  <img alt="Gitea Issues" src="https://img.shields.io/gitea/issues/open/tifflabs/homelab-config?gitea_url=https%3A%2F%2Fwww.tifflabs-software.org%2F&style=for-the-badge&logo=forgejo&logoColor=%23ff0000&labelColor=white&color=ff0000">
</p>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [The Purpose of this repo](#the-purpose-of-this-repo)
- [Introduction: What is a "home lab"?](#introduction-what-is-a-home-lab)
  - [Who is a home lab for?](#who-is-a-home-lab-for)
    - [What hardware should I invest in?](#what-hardware-should-i-invest-in)
- [These are the tools and settings I am using in my home lab.](#these-are-the-tools-and-settings-i-am-using-in-my-home-lab)
  - [Server software](#server-software)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# The Purpose of this repo

The purpose of this repo, as of today, is to document my homelab and network. From here, the scripts, Dockerfiles, Docker Compose files, and markdown files will be imported into my wiki of choice, [Wiki.js](https://js.wiki/). From there, I will update my [draw.io](https://www.drawio.com/) diagrams to explain which devices are on what subnet and the switches each device is connected to.

If you would like more information about documenting your homelab/network setup, there are some excellent resources listed at the end of this README.

# Introduction: What is a "home lab"?

A home lab is basically an over-engineered home networking setup for uber nerds. You can self-host your blog and airgap your IoT traffic with a VLAN on your UniFi Dream Machine Pro or SE, but it really isn't necessary.

Most of us who have home labs have (or in my case, had, at least for the moment) disposable income and a desire to learn, break stuff, get angry, and try again. That's the best part about it besides the gear; getting to understand how the internet and networking works by breaking it.

## Who is a home lab for?
For anyone who has the income and the stubborness to learn how these things work. Once you get your lab setup, it is just three levels away from house guests thinking you're a tech genius.

### What hardware should I invest in?

Start *very, very, small*. I've built up the stuff I have over two and a half years, with the beginning of this year picking up used Intel NUCs from eBay to have a Proxmox cluster to administer self-hosting stuff that I am still learning, deploying VMs to tinker with operating systems and pen testing.

Maybe grab a server rack, a cheap one will do. A good, solid router is a must if you're going to be doing this. Pick up a decent ethernet switch and a dedicated mini PC and get your hands dirty. All this can be had for under $500.

You'll find my setup below.

[☝️ Top](#table-of-contents)

# These are the tools and settings I am using in my home lab.

<!-- ![](https://img.shields.io/badge/homeassistant-41BDF5.svg?&style=for-the-badge&logo=homeassistant&logoColor=white) -->

|     | Device                                                   | Image/Where to Buy (Click the Image)                                                                                          |
| --- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
|     |                                                          |                                                                                                                               |
|     | Used NUCs                                                | [![nucs]](https://www.ebay.com/itm/285116201597?var=586979484256)                                                             |
|     | Intel NUC                                                | [![ha-nuc]](https://www.amazon.com/gp/product/B09DCZQFF2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                     |
|     | UniFi Dream Machine Pro                                  | [![udm-pro]](https://store.ui.com/us/en/pro/category/all-unifi-cloud-gateways/products/udm-pro)                               |
|     | UniFi Flex HD AP                                         | [![unifi-flex-hd]](https://www.amazon.com/gp/product/B07YQ87QBF)                                                              |
|     | TP-Link (T1600G-18TS) 16 Port Managed Switch             | [![tp-link-T1600G-18TS-switch]](https://www.amazon.com/gp/product/B0797KPRPK/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) |
|     | Echogear Server Rack                                     | [![rack]](https://www.amazon.com/gp/product/B07YYJMCNV/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                       |
|     | Generic NUC 1U Rack                                      | [![nuc-rack]](https://www.amazon.com/gp/product/B09BJ5WBHB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                   |
|     | Cyberpower power strip 12 outlets                        | [![cyberpower-strip-12]](https://www.amazon.com/gp/product/B00077INZU/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)        |
|     | Cyberpower power strip 18 outlets                        | [![cyberpower-strip-18]](https://www.amazon.com/gp/product/B004K1YG1Y/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)        |
|     | Synology DS920+ NAS                                      | [![synology-9120]](https://www.amazon.com/gp/product/B087Z34F3R/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)              |
|     | Deco X55 Router                                          | [![deco-x55]](https://www.amazon.com/gp/product/B09PRB1MZM/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                   |
|     | Navepoint 12U Closet Rack                                | [![navepoint-12u-closet-rack]](https://www.amazon.com/gp/product/B072BXSTY8/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)  |
|     | Beelink NUC                                              | [![beelink-nuc]](https://www.amazon.com/gp/product/B0BVLPCDVW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                |
|     | CyberPower LCD UPS System 2U Rack/Tower                  | [![cyber-power-ups]](https://www.amazon.com/gp/product/B00HDODQYS?th=1)                                                       |
|     | Raspberry Pi 4 B 8gb RAM                                 | [![raspberry-pi-4]](https://www.amazon.com/gp/product/B08R87H4RR/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)             |
|     | Beelink S12 Pro Mini PC, Intel 12th Gen Alder Lake- N100 | [![beelink-s12-pro-nucs]](https://www.amazon.com/dp/B0CRKD4YQL?th=1)                                                          |

[☝️ Top](#table-of-contents)

## Server software
Some of the software running on the servers in my home lab.

[Software](/software/README.md)

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
 [raspberry-pi-4]: assets/rpi-4.png
 [raspberry-pi-3B+]: assets/rpi-3bp.png
 [raspberry-pi-2]: assets/rpi-2.png
 [beelink-nuc]: assets/beelink.png
 [beelink-s12-pro-nucs]: assets/beelink-pros.png
 [cyber-power-ups]: assets/ups.png