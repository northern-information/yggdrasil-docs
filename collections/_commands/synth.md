---
weight: 4.1
name: Synth
images: ["clade-synth.png"]
signatures: ["_X_ synth;v;_VALUE_", "_X_ synth;voice;_VALUE_", "_X_ synth;m1;_VALUE_", "_X_ synth;m2;_VALUE_", "synth;enc"]
examples: ["1 synth;v;2", "1 synth;v;toast", "1 synth;m1;99", "synth;enc"]
category: mixer
invocations: ["synth"]
arguments: ["voice", "v", "m1", "m2", "enc"]
---
Set the track's synth voice with `synth;voice;...`. Use either name (`rikki`) or their number (`2`). The Yggdrasil synth has three different polyphonic voices. You can use all three at once, across any number of tracks. 

Set the macro control levels with `synth;m1;...` and `synth;m2;...`. You can use this command with `X` to set entire tracks or `X Y` to set individualslots.

Use `synth;enc` to toggle takeover mode for macro controls with norns encoders 2 and 3.

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