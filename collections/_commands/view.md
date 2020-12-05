---
weight: 1
name: View
signatures: ["view;_VALUE_", "v;_VALUE_"]
examples: ["view;ipn", "view;freq", "v;midi", "v;m1", "v;mixer"]
category: view
invocations: ["view", "v"]
arguments: ["midi", "ipn", "ygg", "freq", "velocity", "vel", "v", "index", "phenomenon", "p", "m1", "m2", "tracker", "t", "hud", "h", "mixer", "m", "clades", "c", "bank", "b", "ypc", "y"]
---
Possible values for slot views are `midi`, `ygg`, `freq`, and `ipn`. Toggle velocity with `velocity`/`vel`/`v`. Reveal the heads up display with column and row numbers with `hud`/`h`.

Similarly, reveal or hide phenomenon with `phenomenon`/`p`. Reveal or hide macros with `m1` and `m2`. `index` is also available to reveal the slot's logical position. Change pages with `tracker`/`t`, `mixer`/`m`, and `clades`/`c` (this can also be accomplished with _tab_).

View current sample bank with `bank`/`b`. Toggle sample names with `ypc`/`y`.