---
weight: 5
name: Shadow / Unshadow
images: ["shadow.png"]
signatures: ["_X_ shadow;_VALUE_", "_X_ sha;_VALUE_", "_X_ unshadow", "unshadow", "unsha"]
examples: ["1 shadow;3", "2 sha;off", "unshadow"]
category: mixer
description: Set a track to "shadow" another's clade and clade attributes. For example, let Track 1 be a MIDI clade set to channel 16 and device 4. By invoking `2 shadow;1`, Track 2 would shadow Track 1. Its clade would be set to MIDI, its channel to 16, and device to 4. Should any of these attributes on Track 1 change, they would also change on Track 2. Shadowed attributes are&#58; clade, synth voice, MIDI channel, MIDI device, crow pair, Just Friends mode. Tracks can shadow other shadowed tracks.
invocations: ["shadow", "sha", "unshadow", "unsha"]
---
