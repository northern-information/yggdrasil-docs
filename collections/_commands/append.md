---
weight: 6
name: Append
signatures: ["_X_ append;_VALUE_", "_X_ ap;_VALUE_", "_X_ append;_VALUE_ shadow", "_X_ ap;_VALUE_ sha"]
examples: ["1 append;3", "1 ap;15", "1 ap;3 shadow"]
category: core
invocations: ["append", "ap"]
arguments: ["shadow", "sha"]
---
Insert a number of tracks after track `X`. Optionally, have each [shadow](#mixer-command-shadow-unshadow) track `X`.
