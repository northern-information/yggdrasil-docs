---
weight: 4.1
name: Synth
images: ["clade-synth.png"]
signatures: ["_X_ synth;v;_VALUE_", "_X_ synth;voice;_VALUE_", "_X_ synth;c1;_VALUE_", "_X_ synth;c2;_VALUE_", "synth;enc"]
examples: ["1 synth;v;2", "1 synth;v;toast", "1 synth;c1;99", "synth;enc"]
category: mixer
invocations: ["synth"]
arguments: ["voice", "v", "c1", "c2", "enc"]
---
Set the track's synth voice and macro control levels. Use `synth;enc` to toggle takeover mode for macro controls with norns encoders 2 and 3.

The Yggdrasil synth has three different polyphonic voices. You can use all three at once, across any number of tracks. Use either name or their number in combination with `synth;voice;` to set.

<div class="table-responsive">
  <table class="table">
    <tr>
      <th>#</th>
      <th>Name</th>
      <th>Description</th>
    </tr>
    <tr>
      <td>1</td>
      <td>PPM</td>
      <td>The norns classic, with parameters pared down to the basics.</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Rikki</td>
      <td>All edges, angular digital angst. Fuzzy nudges through shimmering waves of banshee cries through broken glass.</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Toast</td>
      <td>Minimal FM. Tentative pings to warbly nostalgia to toxic swells.</td>
    </tr>
  </table>
</div>