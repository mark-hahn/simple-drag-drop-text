# simple-drag-drop-text package for the Atom editor

Drag and drop to move text using the mouse. This mimics the standard behavior of many other editors.  Dragging and dropping with the modifier key held will copy the text instead of moving it. You may change the modifier key in the Settings; options are `CTRL`, `ALT`, and `META` (super/Windows/command).

---

![Image inserted by Atom editor package auto-host-markdown-image](http://i.imgur.com/A7IeEag.gif)

---

### Installation

Enter `apm install simple-drag-drop-text` or use the settings page.

---

### Usage

There is no Atom command.  

Drag/drop is triggered by clicking and dragging a text selection from one place to another. If the modifier key is held when the mouse is released then the text will be copied instead of moved. The default modifier key is `CTRL` but you may change this in the Settings to either `ALT` or `META` (super/Windows/command).

### Alternative Package

There is a sister package to this one, `drag-drop-text`.  It offers more features but it has a small learning curve and does not follow the standard behavior of other editors.  This is for true mouse-loving geeks (like me).

Drag-drop-text package features ...

- No need for any modifier key like `ALT` for any operation.  Everything is done with the left mouse button.
- You can do the standard cut (`ctrl-x`), copy (`ctrl-c`), and paste (`ctrl-v`) operations using only the mouse.
- Text that has been dragged is left in the clipboard.  So you can drag and then paste the same text again.

---

### License

Copyright Mark Hahn using the MIT license
Maintained by Geoff Thibeau since 2017-02-08
