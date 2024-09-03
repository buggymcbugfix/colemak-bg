# Vilem's Bulgarian Flavoured Colemak for MacOS

You should probably not use this. I cobbled it together in a few minutes.

## Here goes

### Base

![](assets/0-base.png)

### Shift

![](assets/1-shift.png)

### Option

![](assets/2-option.png)

### Option + Shift

![](assets/3-option+shift.png)

## Bugs

- Command key combos won't work. _Really_ annoying. Please drop me a line if you know how to fix this.
- And more..!

## Installation

I think this should work?

### Step 1

#### Method a

~~~ console
sudo cp colemak-bg.icns colemak-bg.keylayout '/Library/Keyboard Layouts/'
~~~

#### Alternatively, method b

~~~ console
open . && open '/Library/Keyboard Layouts/'
~~~

And then drag and drop.

### Step 2

Restart.

### Step 3

System Preferences > Keyboard layouts > + > scroll, scroll, scroll > Others > Colemak – Bulgarian

### Step 4

Грейт съксес!

## How I made the Icon

Just notes for myself, so not sure if this makes sense to anybody outside of my brain.

1. Get PNG of flag.
2. Make `icon_NxN.png` for `N` in `{64, 32, 16}`, e.g. using Preview's resize feature and save them in a folder called `blah.iconset`.
3. `iconutil -c icns blah.iconset`
