---
layout: post
title: First things to do after a fresh Manjaro Install
date: 2023-06-24 15:28:16 +0900
description: Manjaro Installation
permalink: /manjaro/
img: oh-my-zsh.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Manjaro, Linux]
---
Commands to execute after a fresh installation of Manjaro Linux


```bash
sudo pacman-mirrors --geoip
sudo pacman -Syu
sudo pacman -Sy yay
sudo pacman -Sy base-devel
sudo pacman -Sy telegram-desktop
sudo pacman -Sy python-pip
sudo pacman -Sy flameshot
sudo pacman -Sy neofetch
yay -S code
yay -S slack-desktop
yay -S google-chrome

```