---
weight: 1
topic: Editor
ymode: false
image: screenshot-editor.png
---
- When the buffer is empty, pressing _enter_ activates the editor.
- Pressing _esc_ aborts.
- _&larr;_ and _&rarr;_ move the text cursor.
- _tab_ and _tab_ + _shift_ cycle through the attributes.
- _&uarr;_ and _&darr;_ also cycle through the attributes.
- _mod_ + arrows aborts and moves to adjacent slot.
- Pressing _enter_ at any time commits all **valid** values.
- Pressing _enter_ will do nothing if **invalid** values are present.
- Pressing _enter_ will close the editor if all values are **unchanged**.
- Pressing _enter_ on the YPC field will open a sample selector window. Pressing _esc_ will abandon the window without any updates. Pressing _enter_ on a new sample will commit the new sample along with other values in the editor.
- Entries are validated in real-time. Invalid submissions are not allowed.
- Empty notes and values are valid - it is the same as deleting.
- YGG and MIDI values update each other.
- Spacebar is disabled when the editor is open.
- E1 aborts current edits and selects next not empty slot.
- E2 and E3 still pan X and Y as normal.
