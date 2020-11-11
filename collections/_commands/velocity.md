---
weight: 1.1
name: Velocity
signatures: ["_X_ _Y_ velocity;_VALUE_", "_X_ _Y_ vel;_VALUE_", "_X_ vel;40"]
examples: ["4 3 velocity;127", "4 3 vel;127", "1 vel;40"]
category: musical
invocations: ["velocity", "vel"]
---
Set a slot's velocity value. Unlike most other systems, velocity is mixed with [track level](#mixer-command-level) to produce a final result. For example, a slot with a velocity of 70 on a track with a level of 50% would produce a final velocity of 35. The exception to this rule is the [crow clade](#mixer-command-crow), which can use neither velocity nor track level information.
