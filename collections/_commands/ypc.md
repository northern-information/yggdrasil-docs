---
weight: 4.3
name: YPC
images: ["clade-ypc.png"]
signatures: [
  "_X_ _Y_ ypc;load;_VALUE_",
  "_X_ _Y_ ypc;l;_VALUE_",
  "_X_ ypc;load;_VALUE_",
  "_X_ ypc;l;_VALUE_",
  "ypc;bank;_VALUE_",
  "ypc;b;_VALUE_"
]
examples: ["1 1 ypc;load;909kick.wav", "1 ypc;l;909hat.wav", "ypc;bank;909"]
category: mixer
description: Set a global sample bank and load load samples into tracks and slots.
invocations: ["ypc"]
arguments: ["load", "l", "bank", "b"]
---