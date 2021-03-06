# Dvorak ALT Layouts
Two alternative Dvorak keyboard layouts

One with just the IU keys swapped.
The other with the IU, and LM swapped, with the bonus of swapped shift state for semicolon (;)

![dvorak IULM layout](https://p239.p2.n0.cdn.getcloudapp.com/items/WnuBB7nd/6bffa2c9-6276-46c8-9591-d9d4e09f3aa7.jpg?v=0eb93d054674735078c216777d119a08)

## Installation
Mac:
Download the .DMG file of the layout you want and open the file inside. Select the keyboard layout in System Preferences -> Keyboard.

PC:
Download the PC version of the file (Sorry there is no IU & LM version for PC) extract and open setup.exe. Then select the keyboard layout in the input sources.

## Motivation and theory
After [analyzing](http://patorjk.com/keyboard-layout-analyzer/) other keyboard layouts like colemak, workman, and norman I came to the conclusion that I could get most of the benefits of these layouts in Dvorak without switching to them by simply swapping the I and U keys.

'I' is much more frequently used in English than 'U' so putting it directly under a finger on the home row makes for less movement of the fingers which should lead to faster typing speed. One should theoretically move their fingers less on this layout than on the traditional Dvorak layout. Dvorak with IU swapped even performed better than some of the other layouts like colemak in certain situations.

The same is also true for the 'L' and 'M' keys. L is used more frequently than M so it makes sense to put it in a position that does not strain the right pinky.

Also in programming : is used for more often than ; so I have swapped that keys shift state. That is : on press and ; on shift press.

## Personal experience
I have been using the DvorakIU swap keyboard layout since 2009.

It took me about a week and a half of using this new layout until I was up to my old speed on the official Dvorak layout. In the end I found it easier on the hands than the normal Dvorak layout.

I have been using the DvorakIULM swap since 2018 and have been really enjoying it. The time it took to switch was about two weeks to get back to normal typing speed.

## Karabiner
You may also be interested in my [karbiner config](https://github.com/waynehoover/dotfiles/tree/master/symlinks/karabiner/.config). There I put all the key map changes that I can also use on my laptop keyboard, everything else that can not be ported to my laptop keyboard is in my qmk keymap.

## QMK keymap
I currently use a Kyria as my keyboard and it's great. The keymap I use can be found [here](https://github.com/waynehoover/qmk_firmware/blob/wayne-dvorkakiulm-bilateral-combinations/keyboards/kyria/keymaps/waynehoover/keymap.c).

## Credits
The mac .keylayout file was created with [Ukelele V3](https://scripts.sil.org/ukelele) and should work on all versions of MacOS.
