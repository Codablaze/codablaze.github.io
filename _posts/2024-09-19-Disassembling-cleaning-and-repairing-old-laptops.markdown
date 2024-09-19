---
layout: post
title:  "Disassembling, cleaning and repairing old laptops."
date:   2024-09-19 13:00:00:00 +0100
categories: Learning update!
---

So, after semi-cracking DNS and DHCP servers, then crunching my way through adding Active Directory, I decided to put chapter 2 of the ComptTIA Core 1 exam objectives to bed and focus on chapter 1.

I own a few old laptops from across the years, and one in particular - a Toshiba Satellite from 2010 that has travelled the world with me - was extremely chuggy and running out of steam. I grabbed a large USB stick, back up all the folders, files and photos I could find, and archived them on two other, newer machines.

After that, I took apart the Toshiba, using a guide I found <a href="https://www.youtube.com/watch?v=63G1q-dIE_4">here.<a>

Dismantling it presented me with some challenges, and also taught me a little bit about 'me' and how I do things! I found that I was getting very easily pulled away into side ideas, putting small bolts down in weird places, not exerting fine control, and didn't take time to pick my workspace that well - choosing to place the machine on the edge of a bed while I sat in an office chair. 

My back was hurting quite a bit by the time I moved the laptop to the floor and sat cross-legged.

I then stayed up til 2am troubleshooting WEIRD stuff. Once the laptop was cleaned and reassembled, I tried installing Linux Mint Xfce on it. Linux Mint is a very lightweight operating system that is useful for breathing life into older machines. More info can be found <a href="https://linuxmint.com/">here<a>.

The laptop booted into the installation USB fine, and even ran the install. I decided to wipe Windows 7, and all my documents, rather than install alongside it. Once the installation was complete and I tried to boot the laptop, I got the following error:

"Realtek PCIe FE Family Controller series v1.23 (07/28/10)
PXE-E61: Media Test Failure, check cable

PXE-M0F: Exiting PXE ROM."

Pretty annoying. I retried a few times, but it was past midnight at this point.

Not content with having nothing to show for my efforts, I grabbed ANOTHER old laptop (this time a DELL that I was donated for a community theatre project - it says "ROB" in sharpie on the front). 

My name is not Rob.

This laptop's issue was that it would boot into an error saying "Invalid partition table!" and just restart. I removed its hard drive and swapped it for the one I'd installed Mint Linux on. That didn't boot immediately, so I ran the install process and VOILA! It worked!

After tinkering with a few settings, I replaced all the covers on each laptop (I had four bolts left over - why?) and resolved to approach the problem with a fresh head the following day.

Update:
So, this morning I had a good reflect on last night. I decided to clear myself a proper workspace using my desk and chair, put by a window for some natural light and fresh air. I also set up a small picture frame on its back to store small bolts and brackets in. I have bought myself a parts tray and cheap amazon basics electronics screwdriver set. They arrive in a few days.

After that, I disassembled the Toshiba again, cleaned it again, checked the cables I could access, and tried using the working hard drive in a different slot. I had a HDD/SSD caddy from a HP laptop that fit into the Toshiba, so I seated the SSD in that. It still didn't boot, so I decided to retire that laptop, remove the hard drives and approach the problem another day, once I had more experience.

So now I have experience of handling a small screwdriver, stripping down two laptops, cleaning one inside, and bringing one back to life (It's super quick, I'm using it to write this blog right now!). 

Regarding the Toshiba, this is a perfect opportunity to look into single-boot operating systems like Tails OS and see how they work, because until I understand how to fix a SATA cable a bit better, or work out what the problem is (I did spend an hour looking stuff like BIOS resets etc, but nothing seemed to work), that machine isn't going to be very useful!

I gained a renewed appreciation for how the gap is bridged between hardware and software, and the importance of not randomly putting down tiny bolts in places without thinking!

Now for some lunch, and to plan my next area of study!




