<!-- Document links. Please put all links here to make broken link checking easier. -->
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
[helpdesk]: https://sites.google.com/umich.edu/pat/helpdesk
[training]: https://sites.google.com/umich.edu/pat/training
[checkout]: https://sites.google.com/umich.edu/pat/checkout

[mac-audio-settings]: https://support.apple.com/guide/mac-help/quickly-change-settings-mchl50f94f8f/mac
[ableton-surround-panner]: https://www.ableton.com/en/packs/surround-panner/
[cycling74-ableton-multichannel]: https://cycling74.com/articles/audio-routings-a-new-system-for-multi-channel-routing-in-ableton-live

!> The Control Room manual is incomplete

# The Control Room <small>*Moore 370*</small>

?> The Control Room requires a [certification][training] to use.

The Control Room is a state-of-the-art digital audio studio system that can be used for recording, mixing, and mastering. The control room is connected to nearly every large rehearsal and performance space in the Moore building via a Dante audio network and cameras.

## Known Issues

**Found an urgent issue?** Submit a [Helpdesk Ticket][helpdesk].

Also see [Troubleshooting](#troubleshooting)

<iframe class="airtable-embed" src="https://airtable.com/embed/shrt3ZlN4uSplxlpO?backgroundColor=blue" frameborder="0" onmousewheel="" width="100%" height="600px" style="background: transparent; border: 1px solid #ccc;"></iframe>

## Equipment Overview
?> Links go to item manuals

<!-- tabs:start -->

### **Control Room**
- Avid S6
- Meyer Sound HD1 *x2*
- Genelec 8050B *x5*
- Samsung UN55J6300 TV Monitor 

### **Sidecar Rack**
- LynTec Audio System Power Rack *x2*
- Oppo BlueRay Player
- Tascam LA-80 mkII Unbalanced to Balanced Line Converter
- Oppo BDP-103 CD/BlueRay Player
- Kramer VS-62H 6x2 HDMI Switcher
- Black Box IC402A USB 2.0 over Ethernet *x2*
- Extron SW 2 USB Switcher
- T.C. Electronic System 6000
    - Remote CPU Rack
    - TC Icon Controller
- SurgeX SU-1000Li UPS
- Grace Design m801 Mic Preamp Rack
- 24x2 Longline Patchbay
- Focusrite RedNet 1
- Focusrite RedNet 2
- Blue Sky Bass Management Controller mkII
    - Blue Sky Bass Management Controller Remote
- Avid XMon
- Grace Design m920 High Resolution Headphone Monitoring System
- Shure 450 Series II Talkback Microphone
- Symetrix SX202 Mic Preamp

### **Synth Rack**
- Korg SQ-1
- Sequential Circuits Pro One
- Arp Odyssey
- M-Audio Code 61
- Korg MS-20 Mini
- Moog Subsequent 37 CV
- Korg microKorg
- Gefen USB 2.0 Extender

### **Storage Closet Rack**
- Focusrite RedNet HD32R
- Focusrite RedNet D16R
- 12 port XLRP patch bays *x3*
- 12 port XLRS patch bays *x2*
- Black Box IC402A USB 2.0 over Ethernet *x2*
- Magma ExpressBox 3T Thunderbolt Chassis
    - Avid HDX PCIe Card
    - Universal Audio UAD-2 OCTO Core PCIe DSP Accelerator
- G-Technology 8TB G-RAID External Hard Drive Array with Thunderbolt
- T.C. Electronic System 6000 Mainframe
- SurgeX SU-1000Li UPS *x2*

### **Portable Equipment**
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

## Startup

1. Login to the computer (you will need to do this even if you don't plan on using it)

?><small>Upon your first time signing in to the Control Room computer, you will be prompted to allow Python to make changes. You may also be asked to allow network access for Dante Controller and RedNet Control 2. Click Allow for all the above.</small>

2. Turn on the sidecar rack power switch

3. Turn on relevant speaker set from sidecar rack using the LynTec rack units

<!-- panels:start -->

<!-- div:left-panel -->
4. Unmute the Blue Sky Bass Management Controller Remote on top of sidecar rack (shown on the right)

<!-- div:right-panel -->
![](/_media/blue-sky.webp ':size=50%')

<!-- panels:end -->

## Shutdown
!> Do not turn off any rack equipment. Always turn off using the rack power switch.

1. Turn off speakers from Sidecar Rack using the LynTec rack units
2. Shut down S6 via Home > Settings > About > Shutdown<br><small>See [Navigating the Master Module](#navigating-the-master-module) for more info</small>
3. Turn off sidecar rack power 
4. Log out of the control room computer

## Zero Setting
- <input type="checkbox"> Remove all patch cables and reset all modifications
- <input type="checkbox"> Push black console chairs in front of the S6
- <input type="checkbox"> Push blue chairs to reasonable location or stack
- <input type="checkbox"> Put all equipment in its respective home
- <input type="checkbox"> Cover the S6
- <input type="checkbox"> Close all doors

## Digital Audio Output
?> These guides expect that you will be using the [default Dante preset][dante]

The standard sample rate for the Tech Suite is 48kHz.

<!-- tabs:start -->

### **System Audio**
Make sure that your system audio output is set to **Avid HDX**

> **Tip:** you can do this using [Control Center][mac-audio-settings]

> **Tip:** The **Avid HDX** device will not be available if Pro Tools is open

### **Pro Tools**
You need to make sure to configure Pro Tools to use the HDX playback engine. Usually you only need to do this once.

<!-- panels:start -->
<!-- div:title-panel -->
1. In Pro Tools, go to the menubar and click **Setup > Playback Engine…**
<!-- div:left-panel -->
2. Set the **Playback Engine** to **HDX**
<!-- div:right-panel -->
![](/_media/pro-tools-playback-engine.webp)
<!-- panels:end -->

#### Now you can set up your I/O settings
<!-- panels:start -->
<!-- div:left-panel -->
1. In Pro Tools, go to the menubar and click **Setup > I/O…**
2. In the **I/O Setup** window, click the **Apply to all tabs** checkbox and then click **Import Settings…**
3. Navigate to the Pro Tools Configuration folder. It should have an alias on your Desktop. If not, go to **/Users/Shared/Pro Tools Configuration**.
> **Tip:** Use <kbd>⌘ command</kbd> + <kbd>shift</kbd> + <kbd>G</kbd> to navigate to **/Users/Shared/Pro Tools Configuration**
4. Load the **XMon 5.1.pio** I/O settings file.
5. Check **yes** on the **Replace all buses?** dialog, unless you have special buses setup already

You’ll see (shown on the right) that you now have routings for many different variations of the Main output. These can all be accessed within your project and assigned to tracks. This should work for both 5.1 and stereo projects. By default, new tracks will use a stereo routing.
<!-- div:right-panel -->
![](/_media/pro-tools-5.1.webp)
<!-- panels:end -->

### **Logic Pro**
1. Create a new Logic Pro project or open an existing one
2. In the menubar go to **Logic Pro > Preferences > Audio…**
3. Set the input and output device to **Avid HDX** (make sure Pro Tools is closed)

> **If you are using 5.1:** In Logic Pro: go to the **I/O Assignments** tab, set **Show as** to **5.1 (ITU 775)** and click the **Default** button
>
> ![](/_media/logic-cr-output.webp ':size=50%')

### **Ableton Live**
?> Only enable the outputs you need to save resources. Setting the labels is optional but recommended.

<!-- panels:start -->
<!-- div:left-panel -->
1. In the menubar, go to **Live > Preferences**
2. In the **Audio** tab, set the **Input Device** to **Avid HDX** and **Output Device** to **Avid HDX**
3. Click on **Output Config**
4. Set the output config as shown *(labels optional)*

> Note that Ableton Live is not designed for 5.1 playback. However, Ableton has made a free [Surround Panner][ableton-surround-panner] Max for Live device. Cycling 74' has also made a free [suite of multichannel Max for Live devices][cycling74-ableton-multichannel]. There are also a multitude of other third-party multichannel tools made for Ableton and Max for Live.
<!-- div:right-panel -->
![](/_media/ableton-5.1.webp)
<!-- panels:end -->

### **Reaper**
<!-- panels:start -->
<!-- div:title-panel -->
#### For stereo or 5.1
1. Go to Reaper > Preferences in the menu bar
<!-- div:left-panel -->
2. Ensure your Audio Device is set to Avid HDX
<!-- div:right-panel -->
![](/_media/reaper-preferences.webp)
<!-- div:title-panel -->
#### For stereo
3. Open the routing for your master track and add a hardware output for 1/2
<!-- div:title-panel -->
#### For 5.1
<!-- div:left-panel -->
3. Open the routing window for your master track
4. Set the track channels to 6 as shown in red
5. Add hardware outputs 1-6 as stereo outputs
6. Set the output routing as show in yellow
<!-- div:right-panel -->
![](/_media/reaper-surround-output.webp)
<!-- div:left-panel -->
7. Add ReaSurround (or ReaSurroundPan) to the end of your effects chain on all your tracks (make sure they are set to be 6 channel tracks) and set the speaker layout to 5.1 surround using the dropdown.
<!-- div:right-panel -->
![](/_media/reaper-5.1.webp)
<!-- panels:end -->

> You can use automation to change the panning over time.

### **External Audio**

Use the longline pigtail (usually hanging on the right side of the sidecar) to plug into one of the following:
- **XMon ST Input(s) *(preferred)*:** Use any of the 4 pairs of L/R inputs to go directly to the [XMon](#using-the-xmon-system).<br><small>Note that 1L, 1R, 2L, and 2R are half normalled to the RedNet 1. 4L and 4R are normalled to the Oppo BDP-103 CD/BlueRay Player.</small>
- **RedNet 2 Longline Inputs:** Use any 2 of inputs 9-16 on the RedNet 2. They can be routed using Dante Controller.<br><small>Note that inputs 1-6 are hardwired to the m801. Inputs 7 and 8 are half normalled to the Oppo BDP-103 CD/BlueRay Player.</small>
- **RedNet 1 Longline Inputs:** Use any 2 inputs on the RedNet 1. They can be routed using Dante Controller.<br><small>Note that inputs 1-6 are half normalled the the m801.</small>

<!-- tabs:end -->

## Synth Rack
<!-- TODO -->

## TV
<!-- TODO -->

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

### Navigating the Master Module

<!-- tabs:start -->

#### **Home**
<!-- panels:start -->
<!-- div:left-panel -->
Press the **Home** button to navigate to the home menu
<!-- div:right-panel -->
![](/_media/s6-home.webp)
<!-- panels:end -->

#### **Monitoring**
<!-- panels:start -->
<!-- div:left-panel -->
The **Monitoring** button (which can also be pressed using the physical buttons below the screen) will open the monitoring menu.
<!-- div:right-panel -->
![](/_media/s6-monitoring.webp)
<!-- panels:end -->

#### **Settings**
<!-- panels:start -->
<!-- div:left-panel -->
The **Settings** button (which can also be pressed using the physical buttons below the screen) will open the settings menu.
<!-- div:right-panel -->
![](/_media/s6-settings.webp)
<!-- panels:end -->

#### **Shutdown**
<!-- panels:start -->
<!-- div:left-panel -->
Go to Home > Settings > About > Shutdown
<!-- div:right-panel -->
![](/_media/s6-settings-shutdown.webp)
<!-- panels:end -->

<!-- tabs:end -->

## Using the XMon system
![](/_media/xmon.webp ':size=75%') ![](/_media/xmon-app.webp ':size=12%')

The Avid XMon rack is responsible for routing all the speakers in the Control Room. This rack is controlled by the XMon software utility. The S6 monitoring setup controls the XMon software utility. Both use Avid’s proprietary EUCON protocol to communicate.

> The S6 is able to control parameters of the XMon that are not available in the XMon software utility. See below for how to change monitoring parameters within the S6. If you are still experiencing issues, please see the [Troubleshooting](#troubleshooting) section.

### XMon and the S6
The S6 displays additional configuration options that are not available in the XMon app. To access these settings:

<!-- panels:start -->
<!-- div:left-panel -->
1. Press the **Home** button on the S6 (if you aren't already on the home screen)
<!-- div:right-panel -->
![](/_media/s6-home.webp)

<!-- div:left-panel -->
2. Go to **Monitoring**
<!-- div:right-panel -->
![](/_media/s6-monitoring.webp)

<!-- div:left-panel -->
3. From there you are able to enable and disable individual sources and outputs. You can also adjust the mix volume from there.
<!-- div:right-panel -->
![](/_media/s6-settings-monitoring.webp ':size=50%')
<!-- panels:end -->

> - On the monitoring section of the Master Module you can also switch between the Meyers and the Genelecs as well as adjust the mix volume.
> - There’s also a shortcut **Setup** button next to the monitoring section of the Master Module that will take you directly to the monitor settings
>
> ![](/_media/s6-monitoring-shortcut.webp ':size=30%')

## Microphone Patching
1. Plug your mic into an [AV Panel](/av-panels.md)
2. Patch your mic into a [RedNet MP8R](/dante.md#rednet-mp8r) via the Machine Room [Microphone Patch Bay](/machine-room.md#microphone-patch-bays)
3. Route the MP8R into your desired input via **Dante Controller**
4. [Configure the MP8R and set levels](/dante.md#setting-up-an-mp8r-channel)

### Grace m801
<!-- TODO -->

## Line Level Patching
<!-- TODO -->

## Headphone Monitoring
The headphone monitoring system is contained within a portable rack stored in the Control Room. The rack contains drawers of black ethernet of various lengths and a set of headphones that are intended to be used exclusively with the Aviom system.
<!-- panels:start -->
<!-- div:left-panel -->
1. Ensure the **Aviom D400** is connected to power
2. Ensure the **Aviom D400** is connected to the Dante network via an ethernet cable plugged into the “primary” Dante port. You may need to [patch an AV panel port in the machine room][machine-room#av-data-patch-bay].
3. Set up the **A320 personal mixers** in your desired locations and then connect them to the **A-Net** In ports on the **Aviom D400**
4. **In Dante Controller:** Route your desired outputs (Likely out of the **ControlRoom-SC-RedNetHD32R-HDX**) to the Aviom receiver channels in your desired configuration
<!-- div:right-panel -->
![](/_media/d400.webp 'Aviom D400')

![](/_media/a320.webp 'Aviom A320 personal mixer')
<!-- panels:end -->

The volume of each channel can be set on the **A320 personal mixers**.

?> More information on the Aviom kit can be found [on the inventory system](https://app.cheqroom.com/pHMoanvebv1NemoreoyF74/items/5mhueusqJziGJSHfDcQ9Xm).

## Talkback
<!-- TODO -->

## Troubleshooting

Remember to check the [known issues list](#known-issues)

**Jump to:**
- [No audio output](#no-audio-output)
- [Audio is outputting to every channel](#audio-is-outputting-to-every-channel)
- [No RedNet racks in Dante](#no-rednet-racks-in-dante)
- [S6 is not communicating with Pro Tools](#s6-is-not-communicating-with-pro-tools)
- [S6 is not communicating with the computer](#s6-is-not-communicating-with-the-computer)
- [Dante Controller routing unavailable](#dante-controller-routing-unavailable)
- [HDX driver not showing up in audio devices](#hdx-driver-not-showing-up-in-audio-devices)
- [No output from HDX](#no-output-from-hdx)
- [Computer not waking up](#computer-not-waking-up)

### No audio output

<!-- panels:start -->
<!-- div:left-panel -->
- Ensure the Blue Sky remote is not muted
<!-- div:right-panel -->
![](/_media/blue-sky.webp "Blue Sky :size=50%")
<!-- div:left-panel -->
- Check that XMon utility is set to the USB2MIDI port by right clicking on the dock icon and selecting **USB2MIDI**
<!-- div:right-panel -->
![](/_media/xmon-midi.webp 'XMon MIDI settings')
<!-- div:left-panel -->
1. Check the XMon rack is on. The power button should be illuminated green.
2. Check the XMon utility is communicating with the rack. If you move a slider, a green light should blink on the XMon rack. Also make sure the red mute light is off.
4. Restart the XMon utility and try **step 2** again.
5. Power cycle (turn off and on) the XMon rack, then restart the XMon utility after the mute light turns on and try **step 2** again.

You may need to try this multiple times
<!-- div:right-panel -->
![](/_media/xmon.webp 'XMon Rack')

<!-- div:left-panel -->
- Power cycle the RedNet HD32R. You can find the HD32R under the XLR patch bay in the storage closet.
<!-- div:right-panel -->
![](/_media/HD32R.webp 'RedNet HD32R')

![](/_media/rednet-power.webp 'RedNet Power Switch')
<!-- panels:end -->

### Audio is outputting to every channel
The XMon, in its infinite wisdom (sarcasm), will output to all the main channels if not all the main channels are patched in Dante. Either use a Dante preset or make sure all the XMon channels are routed to *something* in Dante Controller.

> In a recent update, it appears this may be fixed by selecting “mono” or “7.1” in the folddown section on the S6 or using the button on the main fader in the XMon app. However this needs to be tested.

### No RedNet racks in Dante
<!-- panels:start -->
<!-- div:left-panel -->
- Make sure the sidecar rack power switch is on
- Ensure the RedNet units located in the sidecar are indicating they are connected and locked. If not, power cycle the unit.
<!-- div:right-panel -->
![](/_media/rednet-1.webp 'RedNet 1 Unit')

![](/_media/rednet-2.webp 'RedNet 2 Unit')

![](/_media/rednet-power.webp 'RedNet Power Switch')
<!-- panels:end -->

### S6 is not communicating with Pro Tools

<!-- panels:start -->
<!-- div:left-panel -->
1. **In Pro Tools:** In the menubar, go to **Setup > Peripherals…**
2. Make sure **EUCON Control Surfaces** is checked
<!-- div:right-panel -->
![](/_media/pro-tools-eucon.webp)
<!-- panels:end -->

### S6 is not communicating with the computer
<!-- panels:start -->
<!-- div:title-panel -->
1. Restart the S6 driver by clicking the S6 WSControl icon in the menubar ![](/_media/ws-control-error.webp)
<!-- div:left-panel -->
2. Click **Network Setup…**
<!-- div:right-panel -->
![](/_media/ws-control-menu.webp)
<!-- div:left-panel -->
3. Then click **Apply and relaunch**
<!-- div:right-panel -->
![](/_media/ws-control.webp)
<!-- panels:end -->

### Dante Controller routing unavailable
All Dante hardware in the Tech Suite is standardized to a **48kHz** Sample Rate. Use one of the following methods to update the sample rate.
- **Method A:** Change the tab sample rate in RedNet Control (assuming you have all your devices in a tab)
- **Method B:** In Dante Controller, use the Device Config tab in the Device View window and ensure all devices you are using are set to 48kHz.

### HDX driver not showing up in audio devices
If Pro Tools is open, the HDX driver will not show up in other software.

### No output from HDX
1. Open **Audio MIDI Setup**.
2. If the window named **Audio Devices** isn't open, in the menubar go to **Window > Show Audio Devices** or press <kbd>⌘ command</kbd> + <kbd>1</kbd>
3. Select **Avid HDX** (make sure Pro Tools is closed)
4. In the **Output** tab, turn the **Master** fader up (make sure to lower the XMon's volume so you don’t blow out your ears or the speakers)

### Computer not waking up
It may be off. In the storage closet, you will a rack with a [black "trashcan" Mac Pro](https://imgur.com/gallery/lKQRffg) on its side. Press the [power button](https://www.howtogeek.com/440630/how-to-turn-your-mac-on-and-off/) to wake it up.

If the computer doesn't make a startup sound, it may be an issue with the display or peripheral connections. Please don't try to fix it. Submit a [Helpdesk][helpdesk] ticket. 