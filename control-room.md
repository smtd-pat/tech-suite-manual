[av-panels]: /av-panels.md
[clearcom]: /clearcom.md
[control-room]: /control-room.md
[dante]: /dante.md
[edit-rooms]: /edit-rooms.md
[lan]: /lan.md
[machine-room]: /machine-room.md
[mtl]: /mtl.md
[video-switcher]: /video-switcher.md
[workshop]: /workshop.md
[helpdesk]: https://pat.smtd.umich.edu/helpdesk
[training]: https://pat.smtd.umich.edu/training
[checkout]: https://pat.smtd.umich.edu/checkout

# The Control Room <small>*Moore 370*</small>
?> The Control Room requires a [certification][training] to use.

!> This manual page is outdated due to numerous updates to the system and should only be used as a reference. Updates will be made soon...

The Control Room is a state-of-the-art digital audio studio system that can be used for recording, mixing, and mastering. The control room is connected to nearly every large rehearsal and performance space in the Moore building via a Dante audio network and cameras.

## Known Issues
**Found an urgent issue?** Check if its answered in [troubleshooting](#troubleshooting). If not, submit a [Helpdesk Ticket][helpdesk].

<iframe class="airtable-embed" src="https://airtable.com/embed/shrt3ZlN4uSplxlpO?backgroundColor=blue" frameborder="0" onmousewheel="" width="100%" height="600px" style="background: transparent; border: 1px solid #ccc;"></iframe>

## Equipment Overview
?> Links go to item manuals

<!-- tabs:start -->

### **Control Room**
![](/_media/cr-room.webp ':size=50%')
- Avid S6
- Grace m908 Monitor Controller (RCU)
- Meyer Sound HD1 *x2*
- Genelec 8050B *x7*
- Genelec 8340A *x4*
- Auratone 5C *x2*
- Samsung UN55J6300 TV 

### **Sidecar Rack**
![](/_media/cr-sidecar-rack.webp ':size=50%')
- Grace m908 Monitor Controller (ACU)
- LynTec Audio System Power Rack *x2*
- Kramer VS-62H 6x2 HDMI Switcher
- T.C. Electronic System 6000
    - Remote CPU Rack
    - TC Icon Controller
- SurgeX SU-1000Li UPS
- Grace Design m801 Mic Preamp Rack
- 24x2 TT Patchbay
- Focusrite RedNet 2

### **Synth Rack**
![](/_media/cr-synth-rack.webp ':size=50%')
- Korg SQ-1
- Sequential Circuits Pro One
- Arp Odyssey
- M-Audio Code 61
- Korg MS-20 Mini
- Moog Subsequent 37 CV
- Korg microKorg

### **Storage Closet Rack**
![](_media/cr-closet-rack.webp ':size=50%')
- Focusrite RedNet HD32R
- Focusrite RedNet D16R
- 12 port XLRP patch bays *x3*
- 12 port XLRS patch bays *x2*
- Black Box IC402A USB 2.0 over Ethernet *x2*
- Sonnettech xMacStudio with Echo III PCIe Chassis
    - Apple Mac Studio (M1 Ultra, 64 GB Memory)
    - Avid HDX PCIe Card
    - Universal Audio UAD-2 OCTO Core PCIe DSP Accelerator
- G-Technology 8TB G-RAID External Hard Drive Array with Thunderbolt
- T.C. Electronic System 6000 Mainframe
- SurgeX SU-1000Li UPS *x2*

### **Portable Equipment**
![](/_media/cr-portable-racks.webp ':size=50%')

More information can be found on the [checkout system][checkout]

- Red4Pre Portable Rack *x2*
- Grace Mic Preamp portable rack
- Aviom D400-Dante headphone monitoring system portable rack w/ ethernet drawers and headphones
- Aviom A320 personal portable mixer *x8*
- Portable Recording/Performance Dante Rack *x2*
    - Cisco SG350-10MP 10-Port Gigabit PoE Managed Switch
    - RedNet MP8R x2
    - RedNet A16R
    - 16 channel Combojack line in
    - 16 channel XLRP line out
    - 16 channel XLRS mic in
    - Furman M-8x2 Power Distribution Unit

<!-- tabs:end -->

## Quick Start Guide

[View the Quick Start Guide](https://docs.google.com/document/d/1nZsRmK9yBv51Kq1g_L7DeaCBAtM3iawYvvnVvzvJShw/edit?usp=sharing)

This is a printed information packet that is usually on the sidecar rack

Contains information on...
- Power up / shut down
- Basic audio output
- Zero setting
- How to use the Grace m908
- Output channel order

## Startup
1. Login to the computer (optional)
2. Turn on the sidecar rack power switch
3. Turn on relevant speaker set from sidecar rack using the LynTec rack units

## Shutdown
!> Do not turn off any rack equipment. Always turn off using the rack power switch.

1. Turn off speakers from Sidecar Rack using the LynTec rack units
2. Turn off sidecar rack power 
3. Log out of the control room computer (if relevant)

> Please leave the computer on so it can perform updates overnight

## Zero Setting
- <input type="checkbox"> Power down the room
- <input type="checkbox"> Remove all patch cables and reset all modifications
- <input type="checkbox"> Push black console chairs in front of the S6
- <input type="checkbox"> Push blue chairs to reasonable location or stack
- <input type="checkbox"> Put all equipment in its respective home
- <input type="checkbox"> Cover the S6
- <input type="checkbox"> Close all doors

## Monitor Controller
![](/_media/cr-m908.webp ':size=50%')

The Grace m908 controls the speakers in the Control Room.

!> Please do not modify any settings in the setup menu!

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/pZBdihS4UWE?si=JlHOVtxEoJRzfKkL&amp;start=346" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Input Information
Currently the Control Room has 3 input sources:

- 7.1.4 Dante
- 7.1.4 USB - via the m908 USB cable on the sidecar

See how to use these in [Audio Output](#audio-output)

### Output Information

- **CR1** - Stereo output from the Meyer HD-1s
- **CR2** - 7.1.4 output from Genelec 8050Bs
- **CR3** - Stereo output from Auratone 5Cs

See how to use these in [Audio Output](#audio-output)

### Talkback
The talkback microphone is the microphone peeking over the screen of the [S6 master module](#s6-basics).

See how to route the talkback mic in [Talkback](#talkback-1)

## Audio Output
The standard sample rate for the Tech Suite is 48kHz.

<!-- tabs:start -->

### **Via Mac**
Set the output to **7.1.4 Dante** on the m908

#### System Audio
Make sure that your system audio output is set to **Digiface Dante USB**

> **Tip:** you can do this using [Control Center](https://support.apple.com/guide/mac-help/quickly-change-settings-mchl50f94f8f/mac)

#### Pro Tools
You need to make sure to configure Pro Tools to use the Digiface Dante playback engine. Usually you only need to do this once.

1. In Pro Tools, go to the menubar and click **Setup > Playback Engine…**
2. Set the **Playback Engine** to **Digiface Dante**


#### Logic Pro
1. Create a new Logic Pro project or open an existing one
2. In the menubar go to **Logic Pro > Preferences > Audio…**
3. Set the input and output device to **Digiface Dante**

#### Ableton Live
1. In the menubar, go to **Live > Preferences**
2. In the **Audio** tab, set the **Input Device** to **Digiface Dante** and **Output Device** to **Digiface Dante**

### **Via Laptop**
1. Set the output to **7.1.4 USB** on the m908
2. Plug in your laptop to the USB cable hanging on the left side of the sidecar rack and use the **m908** output device.

<!-- tabs:end -->

## TV and Computer Monitor
<!-- panels:start -->
<!-- div:left-panel -->
The TV and computer monitor on the S6 can change inputs using the matrix switcher in the sidecar rack.
<!-- div:right-panel -->
![](/_media/cr-matrix-switcher.webp)
<!-- panels:end -->

### TV

- **HDMI 1** – Input from the matrix switcher in the sidecar rack
- **HDMI 2** – Input from the [Video Switcher](/video-switcher.md)

## S6 Basics
<!-- panels:start -->
<!-- div:left-panel -->
The Avid S6 is a modular digital mixing console/control surface made for use with Pro Tools. It communicates with a computer running a DAW like Pro Tools or Logic Pro using Avid’s proprietary EUCON protocol.
<!-- div:right-panel -->
![](/_media/s6.webp)
<!-- panels:end -->

### Using Pro Tools
In Pro Tools, you must enable EUCON support in order to use it with the S6. You can learn how to enable EUCON in Pro Tools and find troubleshooting tips in the [troubleshooting](#s6-is-not-communicating-with-pro-tools) section.

You should see the details of your session reflected on the console if configured correctly.

### Using Logic Pro
Logic has built-in EUCON support that is enabled by default. If the console is not communicating with Logic, see the [troubleshooting](#s6-is-not-communicating-with-the-computer) section.

You should see the details of your session reflected on the console if configured correctly.

### Modules
The S6 is made up of modules. Our console has a total of 14 modules. *1* Master Module M40, *1* Automation Module, *3* Display Modules, *3* Knob Modules, *3* Process Modules, and *3* Fader Modules.

<!-- tabs:start -->

#### **Master**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Master Module M40** is main computer within the console. It is the brains of the console and controls all other modules. You can use it to control monitoring, talkback, settings, channel parameters, and more.
<!-- div:right-panel -->
![](/_media/s6-master-module.webp)
<!-- panels:end -->

#### **Automation**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Automation Module** allows you to access features from your DAW as well as additional functionality for the selected channel strip.
<!-- div:right-panel -->
![](/_media/s6-automation-module.webp)
<!-- panels:end -->

#### **Display**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Display Module** displays channel information
<!-- div:right-panel -->
![](/_media/s6-display-module.webp)
<!-- panels:end -->

#### **Knob**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Knob Module** contains knobs to control various channel parameters
<!-- div:right-panel -->
![](/_media/s6-knob-module.webp)
<!-- panels:end -->

#### **Process**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Process Module** allows you to select what parameters are controlled by the knob module.
<!-- div:right-panel -->
![](/_media/s6-process-module.webp)
<!-- panels:end -->

#### **Fader**
<!-- panels:start -->
<!-- div:left-panel -->
The **S6 Fader Module** contains the faders along with important buttons like select, mute, and solo. 
<!-- div:right-panel -->
![](/_media/s6-fader-module.webp)
<!-- panels:end -->

<!-- tabs:end -->

## Microphone Patching
1. Plug your mic into an [AV Panel](/av-panels.md)
2. Patch your mic into a [RedNet MP8R](/dante.md#rednet-mp8r) via the Machine Room [Microphone Patch Bay](/machine-room.md#microphone-patch-bays)
3. Route the MP8R into your desired input via **Dante Controller**
4. [Configure the MP8R and set levels](/dante.md#setting-up-an-mp8r-channel)

### Grace m801 Mic Preamp

<!-- panels:start -->
<!-- div:left-panel -->
Patching for the m801 can be found in the Control Room closet. This XLR patch bay exposes inputs from the Machine Room microphone patch bay as well as the Tech Suite AV panels in Hankinson, Watkins, MacIntosh, and Britton. 

The output of the m801 is routed via patch bay outputs **1-8** to transmitters **1-8** on the RedNet 2
<!-- div:right-panel -->
![](/_media/cr-closet-patchbay.webp)
![](/_media/cr-grace.webp)
<!-- panels:end -->

## Headphone Monitoring
The headphone monitoring system is contained within a portable rack stored in the Control Room. The rack contains drawers of black ethernet of various lengths and a set of headphones that are intended to be used exclusively with the Aviom system.
<!-- panels:start -->
<!-- div:left-panel -->
1. Ensure the **Aviom D400** is connected to power
2. Ensure the **Aviom D400** is connected to the Dante network via an ethernet cable plugged into the “primary” Dante port. You may need to [patch an AV panel port in the machine room][machine-room#av-data-patch-bay].
3. Set up the **A320 personal mixers** in your desired locations and then connect them to the **A-Net** In ports on the **Aviom D400**
4. **In Dante Controller:** Route your desired outputs to the Aviom receiver channels in your desired configuration
<!-- div:right-panel -->
![](/_media/cr-d400.webp 'Aviom D400')

![](/_media/cr-a320.webp 'Aviom A320 personal mixer')
<!-- panels:end -->

The volume of each channel can be set on the **A320 personal mixers**.

?> More information on the Aviom kit can be found [on the inventory system](https://app.cheqroom.com/pHMoanvebv1NemoreoyF74/items/5mhueusqJziGJSHfDcQ9Xm).

## Talkback
<!-- panels:start -->
<!-- div:left-panel -->
The talkback microphone is routed through the Grace m908 via its Dante outputs on channels **1** and **2**.

The mic can be controlled via the **Talkback** button on the m908 RCU.
<!-- div:right-panel -->
![](/_media/cr-talkback-mic.webp)
<!-- panels:end -->

## Troubleshooting

Remember to check the [known issues list](#known-issues)

**Jump to:**
- [S6 is not communicating with Pro Tools](#s6-is-not-communicating-with-pro-tools)
- [S6 is not communicating with the computer](#s6-is-not-communicating-with-the-computer)
- [Computer not waking up](#computer-not-waking-up)

### S6 is not communicating with Pro Tools
<!-- panels:start -->
<!-- div:left-panel -->
1. Make sure the EUCON toggle button is viisible on the toolbar
2. Click on the EUCON toggle to turn it on
3. If the EUCON toggle is on, toggle it off and back on again

<!-- div:right-panel -->
![](/_media/sw-protools-eucon.webp)
![](/_media/sw-eucon-select.webp)
<!-- panels:end -->

### S6 is not communicating with the computer
<!-- panels:start -->
<!-- div:title-panel -->
1. Restart the S6 driver by clicking the S6 WSControl icon in the menubar ![](/_media/cr-ws-control-error.webp)
<!-- div:left-panel -->
2. Click **Network Setup…**
<!-- div:right-panel -->
![](/_media/cr-ws-control-menu.webp)
<!-- div:left-panel -->
3. Then click **Apply and relaunch**
<!-- div:right-panel -->
![](/_media/cr-ws-control.webp)
<!-- panels:end -->

### Computer not waking up
It may be off. In the storage closet, you will a rack with a Mac Studio. Press the power button on the back to wake it up.

If the computer doesn't make a startup sound, it may be an issue with the display or peripheral connections. Please don't try to fix it. Submit a [Helpdesk][helpdesk] ticket. 