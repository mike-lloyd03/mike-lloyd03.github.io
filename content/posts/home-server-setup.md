---
title: "I am Fully Self-Hosted Now"
date: 2022-03-21T22:11:31-07:00
draft: false
---

For the most part.

I started this journey towards self-hosting with a Raspberry Pi 2 back in November 2020 and I just finished deleting everything out of my Google Drive and Google Photos. I still have Gmail because it's a good junk mail pit but other than that, I have migrated all of my cloud services to my home server. It feels pretty good to be out of the cloud and to have total ownership of my data.

![Home server](/post-2/server.jpg)

Here's my setup:

## Services

- Document Storage: [Nextcloud](https://nextcloud.com)
  - Of course. I wish there was a less bloaty option but it's the best in the field.
- Document Editing: [OnlyOffice Document Server](https://github.com/ONLYOFFICE/DocumentServer)
  - I tried hard to make LibreOffice work but OnlyOffice is just so clean
- Photo Management: [Photoprism](https://photoprism.app/)
  - Solid Google Photos replacement. Has facial recognition which is a must-have for me.
  - Using Photosync for automatically uploading photos from my phone
- Smart Home: [Home Assistant](https://www.home-assistant.io/)
  - But of course. Awesome app. Wish I could get a job there.
- Network Video Recorder: [Frigate](https://frigate.video/)
  - Seriously one of the coolest parts of my home server. Totally local object detection and 24/7 recording. Better than any paid cloud service garbage.
- Media Streaming: [Jellyfin](https://jellyfin.org/)
  - I tried to get into Plex first but everything beyond the basics cost money and I'm really not going to be using it enough to be worth it.
- VPN: [Wireguard](https://www.wireguard.com/)
  - Classic.
- Server Notifications: [Gotify](https://gotify.net/)
  - Simple app for being notified about certain events on my server
- Log Aggregation: [Graylog](https://www.graylog.org/)
  - It's really not a great app but we use it at work so whatevs.
- Backups: [Restic](https://restic.net/)
  - Great CLI tool for deduping and encrypting backups.
  - Uses the snapshot model and can backup to S3.

## Equipment

- Macbook Pro 2012, i7 2.6 GHz, 16 Gb RAM. Running Arch Linux (btw)
- Intel NUC 5th gen i5, 8 Gb RAM. Running Arch.
- Synology DiskStation NAS DS1019
  - 2x WD Red 4TB
  - 1x Seagate Skyhawk 2TB
  - 2x 500GB NVMe cache drives
- Linksys WRT3200ACM running [OpenWRT](https://openwrt.org/)
- 3x Reolink 4k IP Cameras
- 1x Amcrest IP Camera

## Still on the Cloud

- [ProtonMail](https://protonmail.com/)
- Gmail
- Off-Site backups on [Storj.io](https://www.storj.io/)
- [Bitwarden](https://bitwarden.com/)
   - I was self-hosting this for a while but I figured, for 3 bucks a month or whatever, I can let them handle all my secrets.

## Future Plans

I don't really know yet. I'm pretty happy with my setup. I'd like to get my server put together into a rackmount setup but it's working for now. I'm sure I'll find something else to self-host in another week or so.
