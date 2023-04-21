# Z3R0D4Y Custom Kali VMWare Installation Guide

Quick guide for the installation of [our custom kali VM image](https://drive.proton.me/urls/Z80S491DJ8#XAQLfAfGp9GK). Our image is based on [kali linux's 64-bit WMWare image](https://www.kali.org/get-kali/#kali-virtual-machines), we have made minor changes listed below.

- Default Desktop Background
- Default keyboard changed to danish windows keyboard
- Time changed to match the danish timezone

If you find yourself downloading tools that is often used in CTF's but not installed by default, let us know and then we will add it to our kali image.

If you don't want these changes, this guide will still be valid if you download the [official kali linux vmware image](https://www.kali.org/get-kali/#kali-virtual-machines).

## How to install

*Remember to have virtualization enabled in your BIOS, google your motherboard/machine to find a guide on how to enable it. It should be enabled by default. But if VMWare doesn't work, then it might need to be enabled manually.*

If you don't already have WMWare installed, you can [install it from here for free](https://www.vmware.com/products/workstation-player.html).

First you need to download our WMWare image files. You can [download the compressed files here](https://drive.proton.me/urls/Z80S491DJ8#XAQLfAfGp9GK). When downloaded, extract using [7Zip](https://www.7-zip.org/download.html) or any other 7z compatible decompressors. For convenience, you could move the folder to another place, but it's not necessary.

Open your VMWare application and click on `Open a Virtual Machine`, then you will need to locate the folder you extracted and select the only `.vmx` in that folder. Then your VM should show up in the list of VM's. You can choose to expand the harddisk space, amound of memory and cpu cores as you wish.

<img src="./images/vmware.png" width="600" height="500">

You should now be able to boot into Kali Linux. The default login username and password is `kali`. You can change this if you want to.
