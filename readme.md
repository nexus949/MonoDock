# MonoDock

A simple vertical and horizontal dock with minimal white colored icons.

## Download MonoDock
- Download monoDock here -> [MonoDock](https://github.com/nexus949/MonoDock/releases/download/v1.0/MonoDock_1.0.rmskin).

## Screenshots

#### Vertical
[![mono-Dock-vertical.png](https://i.postimg.cc/XJvzXJfG/mono-Dock-vertical.png)](https://postimg.cc/SXwrvmtk)

#### Horizontal
[![mono-Dock-horizontal.png](https://i.postimg.cc/R0dYMfHx/mono-Dock-horizontal.png)](https://postimg.cc/f33CCVC8)

## How to add more icons ?

Navigate to the skin folder and edit the ```.ini``` file and and paste the template below
```bash
[ICON_NAME]
Meter=Image
ImageName=#@#icons/your_icon.png
W=#IconSize#
H=#IconSize#
X=#BasePosition#
Y=(#BasePosition# + #IconDistance# * The icon number - 1)
SolidColor=0,0,0,1
LeftMouseUpAction=["Path to your application or folder"]
```

## Where to get more icons ?
Get more icons at [Remix Icons](https://remixicon.com/).

## Additional Notes
- Make sure to read ```readme.txt``` for credits and guidance.
- Icons sized at 240 pixels. Icons are in png format and has hex color code of #FFFFFF(white).

## Credits
- This [Rainmeter](https://www.rainmeter.net/) Skin is inspired by [Verticons](https://github.com/irfanfadilah/verticons) created by [Irfan Fadilah](https://github.com/irfanfadilah). I really liked his icon pack so much that I wanted to make my own.