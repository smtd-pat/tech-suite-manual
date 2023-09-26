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

[dante-level-1]: https://www.audinate.com/learning/training-certification/video-tutorials/dante-overview-1-in-getting-started-with-dante-video-series-2
[dante-controller]: https://www.audinate.com/products/software/dante-controller
[download-dante-controller]: https://my.audinate.com/support/downloads/dante-controller
[dante-controller-101]: https://www.audinate.com/learning/training-certification/video-tutorials/video-series-dante-controller-101
[dante-controller-user-guide]: http://dev.audinate.com/GA/dante-controller/userguide/webhelp/
[rednet-4pre]: https://pro.focusrite.com/category/audio-interfaces/item/red-4pre
[dvs]: https://www.audinate.com/products/software/dante-virtual-soundcard
[dante-via]: https://www.audinate.com/products/software/dante-via
[dvs-101]: https://www.audinate.com/learning/training-certification/video-tutorials/dante-virtual-soundcard-4-in-getting-started-with-dante-video-series
[rednet-download]: https://pro.focusrite.com/category/audiooverip/item/rednet-control-2.8

# Dante

Dante is required knowledge to get certified in the Machine Room, Davis Studio, and Control Room. Comprehensive information about Dante is covered in our Dante [training module][training].

Additionally you can review the [Dante Level 1 Certification Training][dante-level-1] from Audinate.

## Important Reminders

- **You should rarely need to use Dante for your routing.** The default preset allows you to make 99% of your patch via the physical patch bays in the Machine Room and Control Room. 
- If you decide to make major changes to device configurations on the Dante network, please load the default preset at the end of your session.
- Please refrain from renaming devices as this can disrupt subscriptions and stop presets from loading correctly.
- When loading the default preset, please take care you are not interrupting someone else’s session.

## Dante Controller
![](/_media/dante-controller.webp ':size=80%')

Dante Controller is used to configure a Dante network.

> The following resources are provided from Audinate, creator of Dante

- [About Dante Controller][dante-controller]
- [Download][download-dante-controller]
- [Dante Controller 101 Video Series][dante-controller-101]
- [User Guide][dante-controller-user-guide]

## How to load a preset
<!-- panels:start -->

<!-- div:left-panel -->
1. Helpful Dante presets for the Tech Suite are placed on your desktop automatically on all the relevant Tech Suite computers.

<!-- div:right-panel -->
![](/_media/presets-folder.webp)

<!-- div:left-panel -->
2. In Dante Controller, click the :file_folder: **Load a Preset** button.

<!-- div:right-panel -->
![](/_media/load-preset-2.webp)

<!-- div:left-panel -->
3. Sometimes the file browser dialog isn’t in the right folder. To get it to the Dante Presets folder, drag it from your Desktop into the dropdown bar at the top of the window.
<br/><br/> Then you can open a preset file.

<!-- div:right-panel -->
![](/_media/load-preset-3.webp)

<!-- panels:end -->

## Creating "safe" presets

By default when you create a preset in Dante Controller, it creates a full-system preset with every parameter. This is undesirable because it means when you load the preset it will change every setting for every device on the network. This not only takes a long time, but it can potentially be extremely disruptive. Hence we ask that you create "safe presets" by only selecting the devices and parameters you need for the preset to work.

<!-- panels:start -->

<!-- div:left-panel -->

1. Set your Dante subscriptions

<!-- div:right-panel -->

![](/_media/dante-controller.webp 'Setting subscriptions in Dante Controller')

<!-- div:title-panel -->

2. Click the :star: **Save Preset** button

<!-- div:left-panel -->

3. Click "Advanced"

<!-- div:right-panel -->

![](/_media/safe-presets-2.webp 'Click the "Advanced" button')

<!-- div:left-panel -->

4. Click the "None" button. Hold down the <kbd>⌘ Command</kbd> key (Use <kbd>Ctrl</kbd> on Windows) and click on the devices you are using.

<!-- div:right-panel -->

![](/_media/safe-presets-3.webp 'Select the devices you are using')

<!-- div:left-panel -->

5. Uncheck everything except:

- Sample rate
- Tx Channel Labels *(if you labeled any channels)*
- Tx Flows
- Rx Channel Names *(if you labeled any channels)*
- Rx Channel Subscriptions

Then click save

<!-- div:right-panel -->

![](/_media/safe-presets-4.webp 'Select relevant parameters for the preset')

<!-- panels:end -->

## Computer audio in/out

There are multiple ways to send a receive audio on the Dante Network

- On the Davis Computer, you can use the Focusrite PCIe Card. Simply select it from the list of audio devices on the computer.
- On the Control Room Computer, you can use the HDX driver. See more on how to use it on the [Control Room][control-room] page.
- You can borrow a Dante interface such as the [RedNet 4pre][rednet-4pre]. We have two of these available.
- In the Edit Rooms and on your personal machine, you can use [Dante Virtual Soundcard (DVS)][dvs]. <br><small>With your personal machine, you will need to purchase a license and be connected to the [Tech Suite LAN][lan].</small>
    - [Getting started with DVS (Video)][dvs-101]
- You can also buy [Dante Via][dante-via] for your personal machine which functions similarly to DVS but with some additional features.

## RedNet

RedNet is Focusrite’s Dante-compatible line of hardware devices.

### RedNet Control 2

<!-- panels:start -->

<!-- div:left-panel -->
The RedNet Control software is used to configure all RedNet hardware (mainly the MP8Rs).

On computers with the Dante Presets folder on the Desktop, there is a **Default Layout.rn2session** file that you can open to set RedNet Control 2 to the default Tech Suite layout.

Please **do not** update the device names using the text box at the top of each device.

- [Download][rednet-download]

<!-- div:right-panel -->

![](/_media/rednet-control-2.webp)

<!-- panels:end -->

### RedNet 2

<!-- panels:start -->

<!-- div:left-panel -->

The RedNet 2 is a 16x16 (16 in, 16 out) Dante audio interface. This device acts as the bridge between the Dante network and the physical world, allowing audio to be fed in and out of the Dante network.

The [Machine Room][machine-room] has three RedNet 2s. All the I/O for the RedNet 2s is exposed in the Tie Line patch bay.

<!-- div:right-panel -->

![](/_media/rednet-2.webp)

<!-- panels:end -->

### RedNet MP8R

<!-- panels:start -->

<!-- div:left-panel -->

The MP8R is a set of Dante-enabled Microphone Preamps. Unlike a traditional preamp, this preamp outputs to the Dante network instead of physical cables.

The [Machine Room][machine-room] has three RedNet MP8Rs. All the I/O for the MP8Rs is exposed in the microphone patch bay.

!> Always open the **Default Settings.rc2snap** preset from the Dante Presets folder at the end of your session.<br/><small>This will reset the settings for the preamps to ensure microphones or other hardware is not accidentally damaged from phantom power or unmuted preamps.</small>

<!-- div:right-panel -->

![](/_media/mp8r.webp)

<!-- panels:end -->

#### Setting up an MP8R channel

<!-- tabs:start -->

##### **Live tab**

<!-- panels:start -->

<!-- div:left-panel -->
The gain of an analog mic preamp can be set by clicking and dragging on the circle dials. You can also double click the number to set a specific value.

You can also click the channel name text to edit the channel name. Make sure to reload the **Default Preset** at the end of your session if you do this.

<!-- div:right-panel -->
![](/_media/mp8r-1.webp)

<!-- panels:end -->


##### **Setup tab**
<!-- panels:start -->

<!-- div:left-panel -->
You get the following parameters for each channel, shown in order

- -20dB Input Pad
- 2.4kΩ Low Impedance Mode
- 48V Phantom Power
- Ø Reverse polarity
- High-pass filter
- Gain compensation — MP8R Dante outputs 9-16 will output a gain-compensated signal, meaning it will attempt to digitally reverse the gain setting from the circle dial. More info can be found in the MP8R manual.

!> Always open the **Default Settings.rc2snap** preset from the Dante Presets folder at the end of your session.<br/><small>This will reset the settings for the preamps to ensure microphones or other hardware is not accidentally damaged from phantom power or unmuted preamps.</small>

<!-- div:right-panel -->
![](/_media/mp8r-2.webp)

<!-- panels:end -->

<!-- tabs:end -->

#### Saving an MP8R preset

If you want to save your channel settings, in the menu bar go to **File > Device Save** and select which devices you want included in the preset. You can load the preset by simply opening the file it creates.