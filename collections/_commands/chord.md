---
weight: 1.2
name: Chord
signatures: ["_X_ _Y_ chord ROOT_PLUS_CHORD_NAME", "_X_ _Y_ c ROOT_PLUS_CHORD_NAME", "_X_ _Y_ c _MIDI_NOTE_;_MIDI_NOTE_;..."]
examples: [
  "1 1 chord;cmaj",
  "1 1 c;bmaj",
  "1 1 chord;60;63;65",
  "1 1 c;60;63;65;72;75",
]
category: musical
description: Paint a chord horizontally starting from `X` `Y`. Automatically append tracks and rows if needed. Any size chord can be built. An extensive [chord library](#digest-chords) available or precision chords can be entered with MIDI values. Chords default to octave 4.
invocations: ["chord", "c"]
---
