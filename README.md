# Gumpy_GBS_Plugins

- Created for the 'Let's Build a Platformer!' course by Gumpy Function.
https://gumpyfunction.itch.io/lets-build-a-platformer
- Made with GB Studio 4.2

#### How to Install
Add the `plugins` folder to your projects root directory.

## Invert Dialogue Background Fill Color
Inverts the text background fill color in dialogue boxes to suit ASCII sheets with white text on black background. Typically, GBS users need to place \007\002 in front of text in a dialogue box to invert the background fill colors, this plugin will ensure you no longer need to put that before all your text throughout an entire project.

![background fill](https://github.com/user-attachments/assets/7bbb984e-6458-44f8-8344-fd76c719e691)

Default background fill (left) and background fill with Invert Dialogue Background Fill Color Plugin applied (right)

NOTE: This will not effect the background fill color in the overlay, only when drawing dialogue using a `Display Dialogue` event.

#### How to Use
Enable or Disable the Plugin in your Project Settings under 'UI Elements+'. You can also toggle it on or off in a script using the 'Engine Field Update' event.

![invert_settings](https://github.com/user-attachments/assets/4c577d66-b688-4c3a-8909-e7a9f19f6ecc)

Special thanks to Mike Leisz (Gud_Graphics) for assisting in the creation of this feature.

## Emote Bubble Duration
Change the amount of time the Emote Bubble stays on screen for (in frames).

![Emote Bubble Duration in Settings](https://github.com/user-attachments/assets/0dc9d8a4-8afb-4dac-9f62-7b1a8d1b7e93)

#### How to Use
Set the time in frames in the Project Settings under 'UI Elements+', or set the value in a script using the 'Engine Field Update' event.
