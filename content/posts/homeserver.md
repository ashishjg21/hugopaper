---
title: "I Built a Home Server."
date: 2021-12-31T11:08:50+05:30
draft: false

---

It all started with ads, my main mission these days was to stop incoming all trackers and blocking ads. I just didn't wanted to see ads anywhere. I use AdGuard to block everything in mobile so it's all good in my mobile but when I use TV or when my mom dad watch YouTube in their mobile it's hard for them to keep watch on AdGuard because it gets hard in some situations.
So why can't I block ads to all the devices 
in local LAN network itself, like filtering I mean.  
After so many searches I found a perfect solution and with alot of bounce features which I'm so obsessed to explore more.


Creating a Home server.  
There's a network-wide software for blocking ads and tracking called AdGuard Home which after you setup will cover all your devices in your local LAN network. Also doesn't need any client-side software. 
It operates as a DND server that reroutes to tracking domain to "black hole" so our devices won't connect to those domains. (I didn't completely understand but it works) 

I will even say more. Adguard - not just an ad blocker, but a full-featured firewall. With its help, you are able to take under your control all apps on your device, allow or forbid the network access - as a whole, to a specific server or even a specific file.

Why AdGuard 
In old ways of blocking, (Adaway)you might have blocked the AdChoices network, but you didn't get rid of the initial ad script loaded from the site's own domain. Hence, half of the page is used for a banner place.
Here in AdGuard it doesn't happen that way, so all no annoying website blank spaces.
At this point I feel I'm sponsorsed by AdGuard but its not like I have huge audience and bring alot of growth in their sales. I just wish more people their rights and 

There is just so much more we can do, like 

- Choose what exactly the server blocks and permits.
- Monitor your network activity.
- Add your own custom filtering rules.
- Most importantly, this is your own server, and you are the only one who's in control.

Chalo we have the solution to our problem but the main thing ' a server'. That is a little rough path I took but i built it.

I used my old PC which was unused for so many days, only when I come home for holidays, I clean and set it up. Again it stays untouched until I return. 
So this was right moment to bring the beast to action. It doesn't have impressive specs but for a server any old PC will be enough.
I choose Arch Linux from the two options I had Manjaro and Arch. Manjaro is recommended but i wanted to it be totally command-line, wanted a hands-on experience. 
Also note: I had no experience when I started in whatever I'm doing, this is just alot of googling and reddit searches, also alot of trail and error.It was Fun and great learning experience. 
So fast-forwarding after installing your favourite distro, I found out what all can be using a server and it's overwhelming besides a adblocker.

- A file cloud using: FileRun - Access and share your files from everywhere, sync your devices and enjoy your photo albums from any device, anywhere in the world. Fast and secure!
- A fantastic password manager: VaultWarden - a.k.a Bitwarden, the best password manager available.
- Your own Office Online/Google Docs: OnlyOffice - integrates nicely with FileRun.
- Your own browser sync: Firefox Sync Server - your history, passwords, form fill info etc no longer shared with 3rd parties and easy to sync from laptop to phone.
- A highly secured reverse web proxy to be able to use all these features via your own domain like https://my.domain.cloud.
- Your own ad-filtering or parental filtering dns server: AdGuard Home - no more ads on any device within your network and even on your phone when you leave the house.
- Your own very fast VPN: Wireguard - Your own VPN server and easy management of clients. To access services you do not want to expose publicly online.
- Your own paper scanning and organizing system Paperless-ng - helps you to automatically archive your household administration and access documents easily.
- Your own media center server JellyFin - Watch your series and movies on any smart TV or device. Also when you leave the home via VPN.
- Automatically follow and retrieve your favourite tv shows and movies Sonarr Radarr Bazarr QBittorrent Because nobody can pay for every streaming service just to watch the few shows or movies they like.
- Pretty dashboards to monitor your server Grafana, Prometheus - Not necessary, but handy and with notifications.
- Your own homepage to quickly access each service in a single webpage. 
 [source](https://github.com/zilexa/Homeserver)

How can someone not be overwhelmed, your own file storing device,your own VPN, your own media server... okk now i will stop I hope your convinced to have a home server😹.

This took alot of time it was never ending (like was stuck in loop in Doctor strange's infinite trap). Just to figure out how to install Arch was very difficult for me and that was just the beginning and I'm not even near to a good Linux user still, yet I'm happily and willing to spend time on this. This is just purely for my future self, if not for anyone, to continue learning Linux platform.