# Gumpy_GBS_Plugins

- by Gumpy Function (I'm hoping to share more in the future once I get a better handle on editing the engine)
- Made with GB Studio 4.1

## Invert Dialogue Background Fill Color
Inverts the text background fill color in dialogue boxes to suit ASCII sheets with white text on black background. Typically, GBS users need to place \007\002 in front of text in a dialogue box to invert the background fill colors, this plugin will ensure you no longer need to put that before all your text throughout an entire project.

![background fill](https://github.com/user-attachments/assets/7bbb984e-6458-44f8-8344-fd76c719e691)

Default background fill (left) and background fill with Invert Dialogue Background Fill Color Plugin applied (right)

NOTE: This will not effect the background fill color in the overlay, only when drawing dialogue using a `Display Dialogue` event.

## How to Install
Add the `plugins` folder to your projects root directory.

## How to Use
Enable or Disable the Plugin in your Project Settings under 'UI Elements+'.

![invert_settings](https://github.com/user-attachments/assets/4c577d66-b688-4c3a-8909-e7a9f19f6ecc)
