---
weight: 5
name: Shadow
images: ["shadow.png"]
signatures: ["_X_ shadow;_VALUE_", "_X_ shadow;off"]
examples: ["1 shadow;3", "2 sha;off"]
category: mixer
description: Set a track to "shadow" another's clade and clade attributes. Set to 0 to disable. For example, let Track 1 be a MIDI clade set to channel 1 and device 1. By invoking `2 shadow;1`, Track 2 would shadow Track 1: its clade would be set to MIDI, its channel to 1, and device to 1. Should any of these attributes on Track 1 change, they would also change on Track 2. Shadowed attributes are: enabled, mute, solo, level, clade, synth voice, synth control 1, synth control 2, MIDI channel, MIDI device, sampler tbd, crow pair. Tracks can shadow other shadowed tracks. Turn off with `X shadow;off`.
invocations: ["shadow", "sha"]
---
