# GDI_Plus_Paint Written in AHK 1.1 by M Wolff
Windows GDI+ Drawing tool compatible with stylus-tablet devices.
</br>
<img width="476" alt="Clipboarder 2023 07 02-003" src="https://github.com/wolfman616/GDI_Plus_Paint/assets/62726599/a6c397a0-9569-41f4-ac81-52a5a941a61b">
<img width="337" alt="Clipboarder 2023 07 03-007" src="https://github.com/wolfman616/GDI_Plus_Paint/assets/62726599/b8b941f0-c60b-4a39-b722-45c668f42570">

</br>
Feature rich art application, exposing offerings from the GDI+ framework.
</br>
Pixelation / Gausian-blur Obfuscation / Redactal
</br>
Featuring Hatches, Tile and brick patterns from Windows 3.1!
</br>
Pen stylus detection and temporary logical separation from main pointer:
Whilst application is active, by hooking mouse 1 and 2, clicks issued byu the stylus will not interact with the oprating system.
</br>
It is not more than a few weeks of work so far. Testing on the mouse input has not been carried out. Only the Pen stylus has been tested. There are numerous bugs with the WM_handlers from gui elements getting confused mostly due to timing discrepencies.
</br>
: 2 do :
</br>
Resolve "WM_Accidental" edge-cases.
</br>
Refactor  undo/redo stages to incorporate the last brush stroke as a seperate bitmap which is then blitted into the overall image, thus allowing for repositioning of last stroke, or cut paste operations. Not sure when this should take place as do not what to interrupt fast-iteration multi-stroke pen operations.
</br>
Reposition underlying gradient to enable a simillar start position for each stroke.
</br>
integrate into screen snip regioning tool. 
