---
layout: post
title: Homelab - My experience using Bazzite
date: 2026-03-24
tags: [homelab, random]
permalink: /blog/bazzite-intro
---

### The Problem
A few years ago, I bought a ROG Ally, mainly because I wanted to play some games I had in a more portable fashion either on my couch or lounging around at the cafe. One of my hobbies is gaming, and I find nice enjoyment in playing it on the go, reminds me pleasantly of times playing my Gameboy in the car while we were on the way to soccer games with my parents. Anyways, I also thought of buying a Steam Deck, which a few of my friends also have, and is also the one I definitely hear about it a lot on YouTube from other folks in the gaming space.

I took all of this into consideration at first and as I wasn't in a rush to buy a new device, I waited a while until sales happened to see which one offered a better deal, as I only had a slight preference to the Ally in terms of power.

Once the Ally X came out, my opportunity came and I was able to snag the standard ROG Ally a few hundred bucks off! 

My main issue I discovered quickly with the Ally is that its general handheld navigation was terrible, and _extremely_ hard to get used to... I mean, look at this, why is everything in a desktop mode like this? (not my photo, one I found on internet)

![bazzite-win](/assets/images/bazzite/bazzite-win.jpg)

I was dealing with first world problems definitely, but I wanted something that worked a bit better for me upon startup, and something that preferably wasn't... Windows. My thought process was that I already use Windows as the OS of choice for my main gaming PC, I could just use an alternative for my Ally. At the time, the Steam Deck was the only device that ran SteamOS, and I really wanted a similar alternative to use for my Ally, which led me down the Bazzite route!

### What is Bazzite
[Bazzite](https://bazzite.gg/) is a Fedora-based distro that is very similar to SteamOS, where it provides essentially the same navigation, without the need for having an actual Steam Deck. 

It has two main navigation areas, where it can be in handheld mode (which is really the core of my solution, it allows me to easily flick between different games), or a desktop mode (which is where you treat it like any other computer, ideally hooked up to an external monitor). (See handheld view below)

![bazzite-linux](/assets/images/bazzite/rog-bazzite.jpg)


### Review & Usability After Months

TLDR: Love it, have only ever had _very_ minor issues. 

One of the quirks that occassionally happens is that my internet connection simply just... stops working. Usually a quick reboot solves the issue, and I don't ever think it's an actual software issue, moreso a hardware issue. It's just one of those quirks I've accepted that happens over the span of a few days without a reboot.

The actual usage and feel of the distro feels very straightforward, and the `ujust` commands are a super unique and fun thing to have within the distro. 

From a handheld usage perspective, I love it since I was able to add a super small overlay over the top corner of the device while I'm playing, since I found many times I would play and lose track of time... which caused it to die on me. Needless to say I would spend another half hour getting back to where I was before it died.

Other aspects I've been learning throughout it have been minor changes, such as the fact that it is Fedora-based, which comes with its own understanding, while all of the other distros I've worked with have been Debian-based, so I've been taking some time to get used to an `apt`-less life :P. 

Now that I'm thinking back to it, I remember having this weird issue where it wouldn't recognize my controller despite being configured from a wired stance. I vaguely remember dealing with that for a few days since I was trying to play Rocket League with my friends, until I realized that there was some Steam settings I needed to change in order to configure the gamepad correctly. 

On a day-to-day stance, my general use case for my gaming PC vs. my Ally has been the following: 
- If I plan on playing solo player games, emulated games, or just lounging around the house for hours at a time: __use the Ally__
- If I plan on playing multi player games or games that require me to run Windows: __use the gaming PC__


### Major Consideratio Before Using Bazzite

Before switching off the native Ally Windows OS, _do your due diligence and check your frequently played games on [ProtonDB](https://www.protondb.com/)_. ProtonDB is the place to check to see how easy your specific game will be to play once switching to a Linux based OS, based on the reviews of other players that also play the game on a Linux based OS. There is a rating system that you'll want to review when looking up your game on ProtonDB. The rating's descriptions can be found by hovering over the rating itself on ProtonDB, but I've also left them below for your sake:
- Native: Runs natively on Linux.
- Platinum: Runs perfectly out of the box.
- Gold: Runs perfectly after tweaks.
- Silver: Runs with minor issues, but generally is playable.
- Bronze: Runs, but often crashes or has issues preventing from playing comfortably.
- Borked: Either won't start or is crucially unplayable.
