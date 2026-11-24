---
title: "Shah65"
github: "https://github.com/shahalthamas/Shah65"
description: "A custom 65% minimalist keyboard using RP2040"
created_at: "2026-11-22"
total_time: "5h 12m"
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

# November 24, 2026: CADDING

I am comfortable using Blender, than Fusion or Onshape, as i have been practicing animations, 3d models on Blender since the start. I noticed that Hack Club doesn't support Blender anymore, Well I have been practicing on Onshape..., So if you could accept this one time ?
<br>
I have added both Onshape as well as Blender files in case of any modification or authenticity required.
<br>
I used the plate.dfx to design the Plate, and then I designed the Bottom and Top based on the PCB and Plate, also leaving enough padding to have underside wires or components (SMD) without colliding with the Bottom FDM.
<br>
This is a lock and click in design, as I wanted to avoid using screws, hence a lock and click-in design also if you could notice, this is extremely compact, yet has an lovely aesthetic look :D !!
<br>
![](https://fabricate.hackclub-assets.com/578026c0a380bb3508e10e1d5e8477dd19939e528b074ce0be7e0e1064bc2df1/image-png/image.png)
<br>
[Onshape Link](https://cad.onshape.com/documents/f1803f145455ec0103fb0303/w/ed14bef00e1f0e3e76f49260/e/63a18fe0a0e5d5b9d507f784?renderMode=0&uiState=6b055399905bbdc01cb6fa95)
<br>
![](https://fabricate.hackclub-assets.com/54d099bce1feaa8fb9b26a8eacf80ca60a07a9d54258cab1c5b176dad33b172c/image-png/image.png)
![](https://fabricate.hackclub-assets.com/f3787e985fbc78ab7ba6e1753d6697e4f1efb997b06ccb9556ad941f19847f36/image-png/image.png)
![](https://fabricate.hackclub-assets.com/04b65a020d100c997c82698c23eda7597a308aaa28af1afb4336cadbce4cc16a/image-png/image.png)

![](https://fabricate.hackclub-assets.com/6915252c316e0da8f16e1f779bdb55b15ce28a0fd9eb1269e55c4ba3994f8cd1/video-mp4/animation.mp4)

**Total time spent: 2h 18m**
