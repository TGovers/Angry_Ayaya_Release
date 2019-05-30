# ANGRY AYAYA

**DO YOU LIKE ANIME? DO YOU LIKE MEMES? DO YOU OCCASSIONALLY PARTAKE IN AUDIO CREATION WHERE YOU DESPERATELY NEED AN ANIME-THEMED PLUGIN???** 

**DON’T LIE MY FELLOW ~~WEEBS~~ ANIME ENTHUSIASTS, WE KNOW YOU DO AND _BOY OH BOY_ DO WE HAVE THE PRODUCT FOR YOU!**

![alt text](https://i.imgur.com/BVEH52G.png "Ayaya")

### /// INTRODUCING ///
### /// ANGRY AYAYA ///

![alt text](https://i.imgur.com/7Wf6Aga.png "Angry Ayaya")

## Table of Contents  
[Angry Ayaya Demostration Videos](#angryayayademonstrationvideos)

[Angry Ayaya TLDR](#angryayayatldr)

[Installation Guide](#installation-guide)

[Angry Ayaya In-depth](#angry-ayaya-in-depth)

[Contributing](#contributing)

[License](#license)

<a name="angryayayademonstrationvideos"/>
<a name="angryayayatldr"/>
<a name="installationguide"/>
<a name="angryayayaindepth"/>

## Angry Ayaya Demonstration Videos

### Song Demonstration

[![IMAGE ALT TEXT HERE](https://i.imgur.com/az9tJKi.png)](https://vimeo.com/339302587)

### White Noise Demonstration

[![IMAGE ALT TEXT HERE](https://i.imgur.com/n7VhvBz.png)](https://vimeo.com/339303323)

## Angry Ayaya TLDR

Angry Ayaya is a simple and intuitive VST plugin with an anime aesthetic. It utilises a 2-parameter IRR filter and a 4-parameter Distortion. Angry Ayaya was designed for use with a multitude of different instruments in mind, such as
* Synths
* Baritone Electric Guitars
* 7/8 String Electric Guitars
* Bass Guitars
* And anything else you want to put through it, it's completely up to you!

Angry Ayaya has full automation and save state capabilities for easy use within your favourite DAW! Currently Angry Ayaya only has a Mac DMG installer, but can be used in Windows via the instructions detailed in the Installation Guide section.

Angry Ayaya was inspired by the internet meme “Ayaya”, click the link to the Youtube video below to **_witness the majesty that is Ayaya_** 

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/9wnNW4HyDtg/0.jpg)](http://www.youtube.com/watch?v=9wnNW4HyDtg)

We created the plugin with the mindset of making a great-sounding plugin first and foremost, with a visually-appealing aesthetic following that. 

We wanted to release Angry Ayaya for free, but if you wish to donate it would be hugely appreciated! We are two university students from Wellington, New Zealand in our final year of a Bachelor of Commercial Music at Massey University. We will always keep this plug-in free, but feel free to throw us a nickel or two via the Paypal button below if you enjoy our work!


<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="YP29EFC3QEU4L" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_NZ/i/scr/pixel.gif" width="1" height="1" />
</form>


We really hope that you enjoy our plugin and make some awesome tunes with it!
Thank you!

-- Team Angry Ayaya --

## Installation Guide

For Mac users, we recommend cloning/downloading the repository to your computer and installing the plugin through the easy-to-use DMG installer

**Step 1: Open This!**

![alt text](https://i.imgur.com/AMAPNsq.png "https://i.imgur.com/AMAPNsq.png")

**Step 2: Open the .pkg found inside for quick and easy installation!**

![alt text](https://i.imgur.com/pk037KJ.png "https://i.imgur.com/pk037KJ.png")

For Windows users, you will need to setup and run the plugin on your computer. For this you will need
* [Projucer](https://juce.com/ "https://juce.com/")
* [Microsoft Visual Studio](https://visualstudio.microsoft.com/ "https://visualstudio.microsoft.com/")

Please refer to a youtube guide or the JUCE website if you are unsure on how to begin! We recommend this [video by Miskat Music](https://www.youtube.com/watch?v=rGzSSNjbXlA "https://www.youtube.com/watch?v=rGzSSNjbXlA") or the [JUCE Tutorials Page](https://juce.com/learn/tutorials "https://juce.com/learn/tutorials").

Another great source of help we can recommend is [The Audio Programmer Youtube Page](https://www.youtube.com/channel/UCpKb02FsH4WH4X_2xhIoJ1A "https://www.youtube.com/channel/UCpKb02FsH4WH4X_2xhIoJ1A") 

## Angry Ayaya In-depth

Angry Ayaya was primarily built with [Projucer](https://juce.com/ "https://juce.com/")/[XCode](https://developer.apple.com/xcode/ "https://developer.apple.com/xcode/") as a plugin suited specifically to those who maybe don’t know their way round plugins, but are wanting something cool and intuitive to add that extra “oomph!” to their work.

It utilises an always-active low-pass IIR filter and an optional distortion. IIR filters stands for an Infinite Impulse Response filter, which is unique with how the decay never really reaches zero (to put it simply!). We choose to use this as we personally thought it sounded the best out of the different kinds of filters that we tested. 

The IIR filter has two parameters that you can change; the frequency Cutoff and the Q-Factor. 
* The Cuttoff knob changes the maximum frequency that the filter will let through (as a low-pass filter)
* The Q-Factor knob changes the resonance or **Q** of the filter

The Distortion feature has four parameters that you can change; the Drive, Range, Blend and Volume. 
* The Drive knob changes the overall drive of the distortion (how "grunty" it is, to put it simply)
* The Range knob changes the overall frequencies of the distortion
* The Blend knob changes the blend between the distortion and the pre-distortion sound (ie the pure audio with just the IIR filter affecting it)
* The Volume knob changes the overall volume of the plugin (**this affects the whole plugin** and is used even if you "turn off" the distortion)

If you want to essentially “turn off” the distortion, just turn the distortion Drive, Range and Blend knobs to their lowest values.

Here is a setup that we recommend to get you started with the plugin. It creates a really subtle distortion with just the low frequencies coming through, creating a nice rumble or pulse depending on what you are putting through it.

![alt text](https://i.imgur.com/xx1Yx0v.png "Angry Ayaya Example Setup")

## Contributing and Inspiration

Currently Angry Ayaya is not open to contribution, but this could change in the future!

Taylor Govers: Processor Editor, Repository/README/License Management, Assistant GUI Editor

Ethan Punter: GUI Editor, Repository Management, Photoshop Editor

For this project, we had inspiration and were helped with code by these youtubers. They make awesome work so please check them out and support them!

[The Audio Programmer](https://www.youtube.com/channel/UCpKb02FsH4WH4X_2xhIoJ1A "https://www.youtube.com/channel/UCpKb02FsH4WH4X_2xhIoJ1A")

[Reon Fourie](https://www.youtube.com/watch?v=iNCR5flSuDs&t=2486s "https://www.youtube.com/watch?v=iNCR5flSuDs&t=2486s")

And of course, huge inspiration from the anime behind the meme [Kiniro Mosaic](https://myanimelist.net/anime/16732/Kiniro_Mosaic "https://myanimelist.net/anime/16732/Kiniro_Mosaic"), the creator [Yui Hara](https://myanimelist.net/people/12541/Yui_Hara "https://myanimelist.net/people/12541/Yui_Hara") and the studio that created it [Studio Gokumi](https://en.wikipedia.org/wiki/Studio_Gokumi "https://en.wikipedia.org/wiki/Studio_Gokumi")  

## License

[GNU GPLv3](https://github.com/TGovers/Angry_Ayaya_Release/blob/master/LICENSE.txt)
