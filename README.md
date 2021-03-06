# OoT input display skin
Ocarina of Time themed input display skin for NintendoSpy, based on the HUD you see in the game. Available both for Nintendo 64 and Gamecube controller. There is also a Collector's Edition/MQ version available.

![input](https://github.com/xwmtp/oot-input-display/blob/master/docs/gc-input-2.gif)

The gif shows the Gamecube OoT version of the input display, but it looks identical to N64 except for the L and Z buttons.

## Download
Please visit the [Releases](https://github.com/xwmtp/oot-input-display/releases) page to download the latest skins. Pick the MQ version if you want grey start, red b and green a buttons like on the Collector's Edition.

Don't download the source code! It doesn't contain the images to make the skin work.

Unzip the downloaded folder containing the skin.xml and images and put it in the ```skins``` folder in the directory where ```NintendoSpy.exe``` is located.

## Color settings
Capture the window in OBS by adding a ```Window Capture``` source.

I recommend using the input display against a dark background in OBS because I think it looks best, but anything works. You can add a ```Color key``` filter to the source to get rid of the black background. Make sure to play a bit with the settings. In particular, I recommend keeping the **similarity** at 1 and putting the **smoothness** to 45.

![settings](https://github.com/xwmtp/oot-input-display/blob/master/docs/obs-settings.png)

The skin shows button inputs by lighting the corresponding buttons up. If you would like the whole display to look a bit brighter/dimmer, add a ```Color correction``` filter to the source to adjust the brightness or contrast, or see the next section.

## Brighter display
The downloaded skin will also have a brighter version of the background image. To use this one instead, open the ```skin.xml``` file in a text editor and put ```<background name="Basic" image="gc-skin-brighter.png"/>``` (GC original skin example). This will make the contrast between buttons being pressed and unpressed smaller though.

## Errors/c-stick not working
If the c-stick doesn't work with the GC controller skin or you get errors when you try to use the GC skins, it might have to do with the decimals dots in the ```rangebutton``` code. Try replacing those dots with commas.

## Requests
If you are interested in variations on this skin, let me know by making an issue and perhaps I could create that!

## Support
Skin made by me ([xwillmarktheplace](https://twitch.tv/xwillmarktheplace)). If you like the skin and would like to support me, please take a look at my channel:)
