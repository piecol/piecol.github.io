---
title: "Isac - tiny SMD vacuum pen"
excerpt: "Designing a custom PCB for the Heltec PSOC"
header:
  image: /assets/IMG/ISAC/cover.jpeg
  teaser: /assets/IMG/ISAC/cover.jpeg
gallery:
  - url: /assets/IMG/ISAC/cover.jpeg
    image_path: /assets/IMG/ISAC/render.jpeg
  - url: /assets/IMG/ISAC/render.jpg
    image_path: /assets/IMG/ISAC/render.jpg
  - url: /assets/IMG/ISAC/open.jpg
    image_path: /assets/IMG/ISAC/open.jpg

author_profile: true
categories: PCB
#date: 2021-05-11 11:30:00 +0000
last_modified_at: 2021-12-21 14:30:00 +0000
toc: true
toc_sticky: true
toc_label: "Table of content"
toc_icon: "bolt" 
---
# Compact design

When I assemble surface mount components in combination with solder paste, I find it quite frustrating to have resistors and caps stuck at the very tip of the tweezers. So I decided to build a suction pen that I could bring with me and could work off the grid.


![ISAC](/assets/IMG/ISAC/cover.jpeg)

Isac is an hambugerized stack of common components:

-5V mini vacuum pump
-500mAh LiPo battery
-TP4056 battery charger (with battery protection circuit)
-1803BK motor driver

![ISAC](/assets/IMG/ISAC/render.jpg)

{% include gallery caption="rendering" %}

# A look inside 


![ISAC](/assets/IMG/ISAC/open.jpg)


The price to build one is around 10€. Print the housing and assemble the parts with minimum effort. The electolithic cap at the motor driver has to be placed horizontally so the motor can fit in the enclosure.

![](/assets/IMG/ISAC/up.jpg)

# In action


{% include video id="0Gh8tZppBw4" provider="youtube" %}

# Donating

Please consider to support me if you find this content helpful

[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-bb005d.svg?style=for-the-badge&logo=paypal)](https://paypal.me/picogizmo)


