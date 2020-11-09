---
weight: 0
name: Level
signatures: ["_X_ level;_VALUE_", "_X_ l;_VALUE_"]
examples: ["3 level;88", "1 l;30"]
category: mixer
description: "Set the level of a track. Valid levels are 0% to 100%. Levels are linear. Unlike most other systems, [velocity](#musical-command-velocity) is mixed with track level to produce a final result. For example, a slot with a velocity of 70 on a track with a level of 50% would produce a final velocity of 35. The exception to this rule is the [crow clade](#mixer-command-crow), which can use neither velocity nor track level information. See [Y Mode interactions](#y-mode-interaction-level), too."
invocations: ["level", "l"]
---
