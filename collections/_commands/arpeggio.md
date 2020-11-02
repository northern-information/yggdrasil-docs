---
weight: 1.3
name: Arpeggio
signatures: [
  "_X_ arp;_VALUE_ _MIDI_NOTE_;...", 
  "_X_ arp _MIDI_NOTE_", 
  "_X_ arp _MIDI_NOTE_;_..._", 
  "_X_ _Y_ arp _MIDI_NOTE_",
  "_X_ _Y_ arp;_VALUE_ _MIDI_NOTE_",
  "_X_ _Y_ arp;_VALUE_ _MIDI_NOTE_;_..._",
  "_X_ _Y_ a;_VALUE_ _MIDI_NOTE_;_..._"
]
examples: [
  "1 arp 60",
  "1 arp 60;63;65;67;63",
  "1 3 arp 60",
  "1 3 arp;2 60",
  "1 3 arp;2 60;63;65",
  "1 a 60;63;65"
]
category: musical
description: Arpeggiate the entire track `X` starting at `Y` with evenly-spaced notes. If `Y` is absent, start at 1. Default `VALUE` of spacing is 0. If multiple `MIDI_NOTES` are used, loop through the notes indefinitely.
invocations: ["arpeggio", "arp", "a"]
---
