# Alternative Scheps Rear Bus (ASRB) Parallel Compression Template for Cubase Pro 11

![Rear Bus Setup](/img/main-bus-routing.png?raw=true)

## Introduction

For an overview of the Scheps Rear Bus parallel compression technique, the video below from Chris Selim is a good explainer.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/0uDYPIYRFDQ/0.jpg)](https://www.youtube.com/watch?v=0uDYPIYRFDQ "The REAR BUSS Parallel Compression Technique in CUBASE")

I've incorporated the rear bus technique into my master template that has a number of other buses for drums and orchestral mixing, but these can be removed to your liking.

All the buses are created using FX channels so routing is a bit more flexible.

## Notes

The rear bus is set up with 4 alternative compressors in dual mono mode. If you use them you will need to enable both instance of the plugins for full stereo processing. You can change these to any compressors you like and change the routing in the track edit panels, they are just here for example.

![REar Bus Compressors](/img/rear-bus-comp-active.png?raw=true)

![Dual Mono Routing](/img/rear-bus-comp-routing.png?raw=true)

If you want to look at another method used for dual mono routing then Chris Selim has another useful video here...

[![IMAGE ALT TEXT](http://img.youtube.com/vi/3wyEZA-TGKk/0.jpg)](https://www.youtube.com/watch?v=3wyEZA-TGKk "DUAL MONO Compression Channel HACKS in CUBASE")

I just chose to do it differently as there as less tracks used, the only thing is that you need to make sure that each instance of the compressor has exactly the same settings as they cannot be linked by VCA, but it's easy to copy and paste settings between plugins in Cubase, or even store your settings as a preset to recall in each instance :)

The Quadrafuzz plugin on the main buses is basically there to give tape warmth and character to each group, not really for distortion.

I've removed all my not stock instruments, effects and track presets, they'll make no sense to you and you may not have the plugins anyway.

Instrument and Audio tracks are disabled by default to reduce system load and template load times. Just right click and choose Enable to be abel to use them.

The Ghost Kick grouping is a way to create and control sidechain signals without them actually being included in the main mix chain. The output is not routed to any of the buses, this means you can create, blend and shape the signal profile as you need, and then route it through Sends to your desired sidechain giving you far more control. I usually use this method for kick drum sidechain control, but can be used on any signal path if needed.

![Dual Mono Routing](/img/ghost-kick-group.png?raw=true)

The tracks in the bass and guitar folders folders are routed through to their respective buses, but are set up to switch route are clean DI signal through the "amp" FX bus if needed, either by enabling the direct routing, or using the sends. This system can be duplicated for rhythm and lead guitars. Strictly speaking it's not entirely necessary, you could just put the amp effects on the single audio track, but this allows for creative double tracking and editing techniques and is bypassed by default.

## Installation & Compatibility

This template was created using Cubase Pro 11, I doubt it will work for previous releases but the installation method is the same so give it a try. Other versions (Elements, Artist etc) don't have the routing options available so this template won't work, but if you the routing video above Chris explains how you can get the same effect.

Download the [Alternative Scheps Rear Bus (ASRB) Parallel Compression.cpr](https://github.com/smadgerano/ASRB/blob/main/Alternative%20Scheps%20Rear%20Bus%20(ASRB)%20Parallel%20Compression.cpr) file from GitHub, and save it to the relevant folder on your machine.

On Windows this is here...

`C:\Users\YOURUSERNAME\AppData\Roaming\Steinberg\Cubase 11_64\Project Templates`

On Mac it's this folder here...

`/Users/YOURUSERNAME/Library/Preferences/Cubase 11/Project Templates`

More details on these can be found [here](https://helpcenter.steinberg.de/hc/en-us/articles/360000327730-Location-file-paths-of-presets-in-Cubase-and-Nuendo-) if needed

You can create subfolders in this directory, or rename the template CPR files as you need, Cubase will still recognize them during the new project dialogue.

You could GIT clone this repo directly into your template folder, but I wouldn't recommend that as it will fill your personal folder up with files you don't need, and backing it up more of a pain.

## Loading the Template

After loading Cubase, select File then New Project to open the New Project dialogue. The ASRB template will be in the **More** section. Then choose your project location as usual.

![New Project Dialogue](/img/new-dialogue.png?raw=true)