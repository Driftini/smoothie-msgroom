<div align="center">
	<img src="https://raw.githubusercontent.com/Driftini/smoothie-msgroom/main/logo.png">
	<img src="https://raw.githubusercontent.com/Driftini/smoothie-msgroom/main/screenshot.png">
	<p>
		Forget the hard, flat color fills.<br>
		<b>Make a jump back to the past.</b>
	</p>
</div>


# Smoothie
**Smoothie** is a custom theme for Windows 96's MsgRoom, intended to resemble the smooth and gradient rich aesthetics of old OSes and apps.

It also adds a few simple animations to further improve the user experience!
![image](https://raw.githubusercontent.com/Driftini/smoothie-msgroom/main/cmdbox.gif)

## How do I install it?
### The quick way...
> If you're not using Firefox, it is highly recommended to download the **compat** variant of the theme from the Releases page. 

Simple: download the latest release's CSS file and, in https://windows96.net, import it in `C:/user/appdata/MsgRoom/themes`.
Finally, open MsgRoom and in the menubar, go from **Session** to **Themes**, then choose **Smoothie**.

### ...and the slow one
Alternatively, you can export the CSS file (only compatible with Firefox) yourself, straight from the source SCSS file.

A word of warning: **this only works on Linux for now.**

First, make sure you have installed `git` and `sass` from your distro's package manager (the package names here are from the Arch repos, no idea if other distros name them differently).

Next up, enter these command lines.
```bash
git clone --depth=1 https://github.com/Driftini/smoothie-msgroom
cd smoothie-msgroom
bash build
```
Once done, you'll find the CSS file in the newly created `out` folder.

Obviously all that's left to do now is import the file in the right path in Win96 and enable it in MsgRoom.

## Why this name?
No idea, really. An old (unrelated) stylesheet I made was called Pancake, so I guessed it would've been cool to keep naming themes after desserts.

## Where can I contact you?
I recommend joining the [Windows 96 official Discord server](https://discord.gg/KCTaM75).

Not only you can talk to me there, but you can also find a lot more people developing cool stuff for the website!
