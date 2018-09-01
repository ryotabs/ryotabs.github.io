---
layout: essay
type: essay
title: A Trial by Fire
# All dates must be YYYY-MM-DD format!
date: 2018-08-30
labels:
  - Linux
  - Terminal
---

To get an overall description of the experience, I also described this project [here](https://ryotabs.github.io/projects/arch). 

## The reasoning

For my first semester at UH Manoa, I bought a 13-inch 2017 Macbook Pro, decked out with the best processor and maximum amount of RAM that was available at the time. I used it for a year before one of my keys started to stop working. That was just the final straw that made me want to run far away from the direction that Apple was going with their computers. The keyboard was probably the biggest issue that I had with it, and I know that sounds like the most trivial thing to complain about, but the typing experience makes or breaks the overall experience. The keys had a short travel distance, making it feel like my fingers were just hammering onto a hard surface, and made my fingers and wrists ache after only 30 minutes of continuous typing. The keyboard was also extremely loud, which made doing homework and writing papers in the library or in a quiet room absolutely impossible, as I did not want to disturb anyone else around me. The typing experience was also important because typing is something that I will be doing a majority of the time, writing code, or technical essays, or sending messages over slack. However, the one thing that I did like was macOS. The overall experience was an absolute delight, the UI was sleek and minimalistic, and working with terminal was a breeze, as opposed to the frustrating experience with command line on Windows. Therefore, I wanted something that was somewhat close to the build quality of a Macbook, had better specs but was cheaper, and was able to handle dual booting windows and linux well. To my luck, I found a good deal on the newest model XPS 15 at my friendly neighborhood Costco, with the 8th generation Intel i7 processor, and paid less than I did for my Macbook Pro, which was nice as I sold the Macbook for almost as much as I bought it for. 

## The decision

I went with Arch Linux because I was attracted to the simplicity of it. It had a 'build your own system' vibe to it, and allows you to know exactly what is on your system to reduce overall clutter. I've used Ubuntu before, and there was just too much bloatware on it, like the native Amazon app that was included in 16.04. I have used elementaryOS, which was aesthetically simmilar to macOS, but application support for it wasn't the greatest. One of the best appeals of Arch Linux is the [Arch User  Repository](https://aur.archlinux.org/). The AUR contains custom packages that are developed by users, and greatly expands the pool of available software to install. It was also a do-it-yourself system, meaning that the user is responsible for ensuring that the system is configured correctly, and is expected to tinker with the system to learn it. With this in mind, I downloaded the disk image for Arch linux, created a bootable USB, and booted to the USB to begin the installation.

## The process

I was greeted with a blank terminal screen, and instantly thought I was in over my head. However, I took a breather, pulled up the [Arch wiki](https://wiki.archlinux.org/index.php/installation_guide), and followed the process. The installation stayed true to Arch's simplistic reputation, as I had to manually set and configure things like the keyboard layout, timezone, hard drive partitioning, accommodating UEFI boot, connecting and configuring network access (probably the most frustrating part) and install a bootloader, all from the terminal screen. This ensured that I needed to be comfortable with typing commands in the terminal, or else I would have just sunk to the bottom. This also gave me the opportunity to learn a text editor called Vim, which was one of the editors that was reccommended by the Arch Linux community. After reading about the [benefits of Vim](https://stackoverflow.com/questions/597077/what-are-the-benefits-of-learning-vim), I decided to make it my editor of choice. 

Once I had the bare essentials of a working system, it was finally time to get a display manager!

## Making things pretty

I'll admit, I'm not really a fan of any of the desktop environments that are provided in Linux (okay maybe XFCE is a small exception as I have used it in the past and enjoyed it), as it seemed inferior to the UI of macOS. However, after some research, I came across window managers. A window manager is basically just a graphical environment that consists of tiled windows that can be accessed with various key bindings. The goal of these window managers is to be minimalistic, but still have a high degree of productivity and workflow, and after using it for a while, I can defintely agree. My window manager in particular, i3, is highly customizable via a simple configuration file that can be edited with Vim, or your text editor of choice. In fact, the customization of the graphical environment as a whole is edited from configuration files. You can see my configuration files [here](https://github.com/ryotabs/config-files). 
