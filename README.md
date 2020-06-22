# Retro Midnight commander skins

## What is here?

Here are the Midnight Commander skins from similar programs for DOS and Windows:

* Norton Commander (for DOS)
* Volkov Commander (for DOS)
* Far Manager (for Windows, still in development: https://www.farmanager.com/)

I tried to make skins as similar as possible but with preserving MC usability. So there are these differences:

* originally, there are some special dialogs with special colors (like in `Find File`). Midnight Commander has not a special color scheme for it, so it is the same as the rest
* in other commanders, there are no special colors for different file types. Some of types did not even exist. Skins here keeps colors from Midnight Commander (because of usability)
* some of visual properties is not possible to achieve in Midnight Commander, like different color of buttons, or dialog padding
* I did not change colors of `Diff Viewer`, and only some colors from `Help`. If you would like to improve this, make a pull request :-)

## How to use it?

Download skin `.ini` files to `~/.local/share/mc/skins` (create directory if needed). Then, (re)run Midnight Commander and in menu (`F9`) => `Options` => `Appearance`, new skins will be present. You can choose it. After selecting, don't forget to `Options` => `Save Setup` to preserve this skin in next runs.

I'm using Volkov Commander skin for everyday use and it is usable very well. If you would have any questions or so, write me to ales.janda@kyblsoft.cz.
