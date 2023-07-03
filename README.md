# GDI_Plus_Paint
Windows GDI+ Drawing tool Compatible with stylus tablets
</br>
<img width="476" alt="Clipboarder 2023 07 02-003" src="https://github.com/wolfman616/GDI_Plus_Paint/assets/62726599/a6c397a0-9569-41f4-ac81-52a5a941a61b">
</br>

Feature rich art application, exposing offerings from the GDI+ framework.

Pixelation / Gausian-blur Obfuscation / Redactal

Featuring Hatches, Tile and brick patterns from Windows 3.1!

Pen stylus detection and temporary logical separation from main pointer:
Whilst application is active, by hooking mouse 1 and 2, clicks issued byu the stylus will not interact with the oprating system.

It is not more than a few weeks of work so far. Testing on the mouse input has not been carried out. Only the Pen stylus has been tested.

: 2 do :
Refactor  undo/redo stages to incorporate the last brush stroke as a seperate bitmap which is then blitted into the overall image, thus allowing for repositioning of last stroke, or cut paste operations. Not sure when this should take place as do not what to interrupt fast-iteration multi-stroke pen operations.

Reposition underlying gradient to enable a simillar start position for each stroke.
