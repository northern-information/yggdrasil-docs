---
weight: 1.6
name: Clock
signatures: ["_X_ clock;_VALUE_"]
examples: ["1 clock;.5", "1 clock;.125", "1 clock;2", "1 clock;13.53"]
category: musical
invocations: ["clock"]
---
Set the "clock" value for a track. Default is 1. Max is 2. Tracks have independent clock sync rates.

Yggdrasil uses 96 [PPQN](https://en.wikipedia.org/wiki/Pulses_per_quarter_note), so any value entered will be snapped to the nearest pulse.
