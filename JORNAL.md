---
title: "Shah65"
github: ""
description: "A custom 65% minimalist keyboard using RP2040"
created_at: "2026-11-22"
total_time: "2h 54m"
---

# November 23, 2026: Schematic

I wanted to make a compact keyboard, for utility as well as aesthetics...
<br>
I decided to go with RP2040 as This is my first SMD keyboard, SMD so as to keep it minimalist and compact hence.
<br>
I went through the Raspberry RP2040 docs, datasheet, and their open source RP2040 based devoboard and used it as an reference and designed the keyboard around it.
<br>
I used https://github.com/ebastler/marbastlib as my library as they have vast amount of footprints related to Keyboard and most of them are globally available parts.
<br>
Did a quick Self-Sanity check and everything seemed correct. And then polished it, by categorizing it and drawing box around each category.
<br>
![](https://fabricate.hackclub-assets.com/c5fc2acb6cc885247d9b635ed43918ce8774161b90c18872573a19afbdb53abb/image-png/image.png)
<br>
![](https://fabricate.hackclub-assets.com/7a93ec66476dbcf97868e81d2e3d61fc35c94e81852d7cf1224c8bad7d99fa06/image-png/image.png)

**Total time spent: 1h 30m**

# November 23, 2026: PCB routing

Once the schematic was done and ready, I moved forward with the PCB design
<br>
I used https://www.keyboard-layout-editor.com/ for a quick placement of footprints on PCB editor (KiCAD 10), and them routed them with ease, since this had the MCU and switchs all on the same board 2 layer was not practical hence switched over to 4 layer and was able to route it.
<br>
I would like to add per key RGB led, but thats for v3 I guess, taking it step wise, from THT to SMD to RGB :)
<br>
After doing a DRC, I got a couple of silkscreen error, but other than that everything was fine.
<br>
![](https://fabricate.hackclub-assets.com/a1350ef6fb9fee2da964a77f154f8131700e9388f4977b3f6e30e872f2dffb91/image-png/image.png)
<br>
![](https://fabricate.hackclub-assets.com/585f2aa70f08db63b03aca79c6eecc3379059220069d10e9a01e8a1c862be096/image-png/image.png)

**Total time spent: 1h 24m**
