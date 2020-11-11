---
weight: 4.1
name: Synth
images: ["clade-synth.png"]
signatures: ["_X_ synth;v;_VALUE_", "_X_ synth;voice;_VALUE_", "_X_ synth;c1;_VALUE_", "_X_ synth;c2;_VALUE_", "synth;enc"]
examples: ["1 synth;v;2", "1 synth;c1;99", "synth;enc"]
category: mixer
invocations: ["synth"]
arguments: ["voice", "v", "c1", "c2", "enc"]
---
Set the track's synth voice and macro control levels. Use `synth;enc` to toggle takeover mode for macro controls with norns encoders 2 and 3.
