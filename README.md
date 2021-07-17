# GalaxyBuds2-Leak
I just found a beta-release of the new unreleased Samsung Galaxy Buds 2 plugin on Samsung's update servers. I've tried to collect all interesting data I was able to retrieve.

## Resources

There are pictures of the earbuds in various colors: black, white, gray/green, violet, and yellow

| ![home_image_black](resources\res\drawable-xxhdpi\home_image_black.png) | ![home_image_violet](resources\res\drawable-xxhdpi\home_image_violet.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![home_image_green](resources\res\drawable-xxhdpi\home_image_green.png) | ![home_image_white](resources\res\drawable-xxhdpi\home_image_white.png) |
| ![home_image_yellow](resources\res\drawable-xxhdpi\home_image_yellow.png) |                                                              |

The APK did not contain any battery case images (except simple line-art that matches the Buds Pro and Buds Live case)

### Home-screen widget preview

![widget_preview_buds_controller](resources\res\drawable-xxhdpi\widget_preview_buds_controller.png)

### Cover widget preview

![cover_widget_preview](resources\res\drawable-xxhdpi\cover_widget_preview.png)

## New features

* The app adds an option to enable "ANC with one earbud". It is located in the hearing enhancements fragment; however, it is currently invisible. It will probably be available if the app detects that the connected earbuds have a certain firmware that supports it installed. 
* The app also contains code for an interactive tutorial that is supposed to help the user wear the earbuds correctly (similar to the Buds Live)
* You can now enable/disable 'single-tap', 'double-tap', 'triple-tap', and 'touch-and-hold' touch-actions individually, instead of locking the whole touchpad.

## Battery capacity

| Earbuds  | Case     |
| -------- | -------- |
| 61mAh    | 472mAh   |
| 5V, 0.2A | 5V, 0.6A |

(See screenshots below)

## Comparison with the Buds Pro

- No 360° sound feature
- No 'outside double-tap volume controls' for now. While there's still logic for it in the Bluetooth backend present, this feature was completely stripped from the UI code. They might re-introduce this later with a firmware and app update.
- ANC and Ambient sound are available as well
- ANC does not have the "High/Low" option anymore. You can't fine-tune it; however ANC can now be used even if only one earbud is connected.
- Very precise touch options (read more below; they might add this to the other models as well)

## Screenshots

I'm patching the app on-the-fly to simulate a pair of Buds2. The battery dashboard has been redesigned and is much simpler. Some settings like the Bixby Voice-wakeup and 'ANC with one earbud' are invisible, I didn't bother patching all of those in as well, but they exist.

| ![photo_2021-07-17_16-14-33](screenshots\photo_2021-07-17_16-14-33.jpg) | ![photo_2021-07-17_16-14-45](screenshots\photo_2021-07-17_16-14-45.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

The new touch options (including some info pages):

| ![photo_2021-07-17_16-14-29](screenshots\photo_2021-07-17_16-14-29.jpg) | ![photo_2021-07-17_16-14-28](screenshots\photo_2021-07-17_16-14-28.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![photo_2021-07-17_16-15-04](screenshots\photo_2021-07-17_16-15-04.jpg) | ![photo_2021-07-17_16-15-02](screenshots\photo_2021-07-17_16-15-02.jpg) |
| ![photo_2021-07-17_16-15-00](screenshots\photo_2021-07-17_16-15-00.jpg) |                                                              |

And here are some other various screenshots. The Equalizer settings are the same, and the 'Find my earbuds' page has been redesigned a little bit.

| ![photo_2021-07-17_16-14-41](screenshots\photo_2021-07-17_16-14-41.jpg) | ![photo_2021-07-17_16-14-31](screenshots\photo_2021-07-17_16-14-31.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![photo_2021-07-17_16-15-06](screenshots\photo_2021-07-17_16-15-06.jpg) | ![photo_2021-07-17_16-14-39](screenshots\photo_2021-07-17_16-14-39.jpg) |



### Other stuff

New model number: `SM-R177`
