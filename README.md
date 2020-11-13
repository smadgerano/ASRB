# Alternative Scheps Rear Bus (ASRB) Parallel Compression Template for Cubase Pro 11

Alternative Scheps Rear Bus (ASRB) Parallel Compression Template for Cubase Pro 11



https://www.youtube.com/watch?v=0uDYPIYRFDQ

More flexible than Scheps because effectively all buses can be routed through the rear bus.

Routing

Dual mono compression on the rear bus

# Alternative Scheps Rear Bus (ASRB) Parallel Compression Template for Cubase Pro 11

[![IMAGE ALT TEXT](http://img.youtube.com/vi/0uDYPIYRFDQ/0.jpg)](https://www.youtube.com/watch?v=0uDYPIYRFDQ "Video Title")

## Introduction

For an overview of the Scheps Rear Bus parallel compression technique, the video above is a good explainer.

All the buses are created using FX channels so routing is a bit more flexible.

The Quadrafuzz plugin on the main buses is basically there to give tape warmth and character to each group, not really for distortion.

I've removed all my not stock instruments, effects and track presets, they'll make no sense to you and you may not have the plugins anyway.

Instrument and Audio tracks are disabled by default to reduce system load and template load times.

The tracks in the bass and guitar folders folders are routed through to their respective buses, but are set up to switch route are clean DI signal through the "amp" FX bus if needed, either by enabling the direct routing, or using the sends. This system can be duplicated for rhythm and lead guitars. Strictly speaking it's not entirely necessary, you could just put the amp effects on the single audio track, but this allows for creative double tracking and editing techniques and is bypassed by default.

The Ghost Kick grouping is a way to create and control sidechain signals without them actually being included in the main mix chain. The output is not routed to any of the buses, this means you can create, blend and shape the signal profile as you need, and then route it through Sends to your desired sidechain giving you far more control. I usually use this method for kick drum sidechain control, but can be used on any signal path if needed.

The rear bus is set up with 4 alternative compressors in dual mono mode. If you use them you will need to enable both instance of the plugins for full stereo processing. You can change these to any compressors you like and change the routing in the track edit panels, they are just here for example.

## Installation

Download the [Alternative Scheps Rear Bus (ASRB) Parallel Compression.cpr](https://github.com/smadgerano/MSDS/blob/master/Multiband%20Sound%20Design%20%26%20Sampling%20(MSDS).cpr) file from GitHub, and save it to the relevant folder on your machine.

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

