---
weight: 1.3
name: Arpeggio
signatures: ["X arp MIDI_NOTE", "X arp;VALUE MIDI_NOTE", "X arp MIDI_NOTE;...", "X Y arp MIDI_NOTE", "X Y arp;VALUE MIDI_NOTE", "X Y arp;VALUE MIDI_NOTE;..."]
examples: ["1 arp 60", "1 arp 60;63;65;67;63", "1 3 arp 60", "1 3 arp;2 60", "1 3 arp;2 60;63;65"]
category: musical
description: Arpeggiate an entire track starting at _Y_ with evenly-spaced notes. If _Y_ is absent, start at 1. Default _VALUE_ of spacing is 0. If multiple MIDI notes are used, loop through the notes indefinitely.
invocations: ["arpeggio", "arp", "a"]
---
