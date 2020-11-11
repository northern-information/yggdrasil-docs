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
invocations: ["ypc"]
arguments: ["load", "l", "bank", "b"]
---
Set a global sample bank and load samples into tracks and slots. Yggdrasil can access one bank at a time, but a bank can contain any number of samples. Slots contain can contain up to one sample, but tracks can contain any number of slots (each with unique samples.) "Banks" located at `/dust/audio/yggdrasil/banks/`. 

Yggdrasil ships with a default `factory` bank.

If a filename has frequency information at the end, like `your_sample_name_440hz.wav`, Yggdrasil will repitch intelligently. Once a sample is loaded into a slot, a note value also needs to be set. A common technique is to use `x ypc;l;your_sample_name_440hz.wav` and then use `x arp`.
