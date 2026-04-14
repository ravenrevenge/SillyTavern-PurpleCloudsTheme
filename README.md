# SillyTavern-PurpleCloudsTheme
A SillyTavern theme inspired by soft pastel purples, and probably my love for sailor moon.

![Main page](/src/screenshot-main.png)

My first theme! I was really excited the moment I knew I could add themes. I was inspired by [Selenis' Lavander blossoms theme](https://discord.com/channels/1100685673633153084/1344396649245577307) I installed it first and started tinkering... until I made it look completely different. It has the same type of tones, I darkened them slightly and matched them to the backgrounds. I also have to thank her for the [original Info Board](https://discord.com/channels/1100685673633153084/1344396649245577307/1344396685983350884) that I after used for inspiration to make others. I have both regex for her original plus the ones I made after. It really helps the AI keep more track and consistency on the RP.

## How to use
First of all you need the extension [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs) so all the colors, fonts and CSS load properly, but it gives you more control to edit the theme, if you want to adapt it more to your liking. All the colors can be changed, except for some hardcoded colors on the info board.

Once you have the extension downloaded, in the **"User Settings"** tab import the theme from the folder `theme` called `Purple Clouds.json`. The theme is fully installed now!

### Moonlit Echoes version
To install the theme in Moonlit Echoes you have to add two files instead of one. In the **User Settings** tab import the theme from the folder `theme` called `Purple clouds - Moonlit Echoes - Theme.json` and in the **Extensions** tab import the Moonlit Echoes preset `Purple clouds - Moonlit Echoes - Preset.json` into the extension's settings. Now the theme is fully installed.

![Settings page](/src/screenshot-settings.png)

In the screenshot you can see the extra three colors, and you can change the placement of the QR buttons, and having the default fonts if you're not keen into the cutesy ones I added. The CSS has some annotations too, in case you want to change something like the banner or remove the rainbow avatar frame, which by the way, adapts to all avatar styles!

## Info Board

![chat page](/src/screenshot-chat.png)

To use the info board, you need to be using the **"Chat Completion"** API, import the [extra prompt](https://discord.com/channels/1100685673633153084/1344396649245577307/1344496317438890044) on the **"AI Response Configuration"** and the regex file from the folder `info board` goes into the **"Extensions"** tab.

In the `info board` folder you will find three different info boards:
- **Default** is the regex for Selenis' original prompt. Add the prompt `prompt-[info_board]__default.json` and the regex `regex-[info_board]__default.json` 
- **Cozy** for an edited version more focused on slice of life. Add the prompt `prompt-[info_board]__cozy.json` and the regex  `regex-[info_board]__cozy.json`
- **Emoji** A more simple info board, the categories are emojis and have less information. The one I'm using now, just enough to keep the LLM more consistent in location, time and what the character is wearing. Add the prompt `prompt-[info_board]__emoji.json` and the regex  `regex-[info_board]__emoji.json`

### Cozy Info Board
![Cozy Info Board](/src/IB-Cozy.png)

### Emoji Info Board
![Emoji Info Board](/src/IB-Emoji.png)

> [!NOTE]
> The credit for the default info board goes to @Selenis, the others are based on her original one. Find Selenis' themes and prompt in SillyTavern discord

### Sources and credits
- @Selenis for making the theme that inspired this, and [Rivelle](https://github.com/RivelleDays) for hyping me up when I shared screenshots on discord.
- [IceFog](https://github.com/IceFog72/) for the handy [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs) and the input on the theme.
- [qwerasd205](https://github.com/qwerasd205) for the most adorable monospaced font ever [Annotation Mono](https://qwerasd205.github.io/AnnotationMono/).
- [Looney patterns](https://looneypatterns.com/) for the stars SVG background on the info board.
- [RawPixel](https://www.rawpixel.com/image/18423757/png-pastel-kawaii-divider-flowers-background-purple) for the header png.
- [Ana Tudor](https://codepen.io/thebabydino/pen/bGPMOpJ) for the css rainbow border.
- [Comehope](https://codepen.io/comehope/pen/YLqbXy) for the css stripes border.
- 480 Design for their [Solar icon set](https://icon-sets.iconify.design/solar/?suffixes=Bold%20Duotone)

### Disclaimer
The backgrounds were generated with ComfyUI by me, you can use them if you want, or if you prefer something else... it's totally up to you. The one I use in the captures is `Purple_Clouds_05.png`.
