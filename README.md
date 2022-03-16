# MX Master 3 using logiops for GNOME and/or KDE Plasma
This is a sample config for remapping buttons on a 
[Logitech MX Master 3](https://www.logitech.com/en-us/product/mx-master-3.910-005620.html?page=mx-for-coding) using [PixlOne/logiops](https://github.com/PixlOne/logiops).

## Gestures
The MX Master allows to bind gestures to all buttons. To use them just press the button and move the mouse in the desired direction. While using gestures the cursor does not move

## Keybinds for GNOME (logid.gnome.cfg)
Key | Press | Gesture Up | Gesture Down | Gesture Left | Gesture Right
----|-------|------------|--------------|---------------|-------------
Back|Back
Forward|Forward
Middle (Mousewheel)|default|||
Extra (under Mousewheel)|default||||
Thumb|Activities overview|Applications||Move to the right virtual desktop|Move to the left virtual desktop

## Keybinds for Plasma (logid.plasma.cfg)
Key | Press | Gesture Up | Gesture Down | Gesture Left | Gesture Right
----|-------|------------|--------------|---------------|-------------
Back|Back
Forward|Forward
Middle (Mousewheel)|default|||
Extra (under Mousewheel)|default||||
Thumb|Overview|Move to the virtual desktop 2|Move to the virtual desktop 1||

## CIDS

CID|Mouse Key
---|---------
0x50|Left Mouse Button
0x51|Right Mouse Button
0x52|Middle Mouse Button
0x53|Back Button
0x56|Forward Button
0xc3|Thumb Button
0xc4|Extra Button (under Mousewheel)

## List of key codes

[List of key codes](https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h).