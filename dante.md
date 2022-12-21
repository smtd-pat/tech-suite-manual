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
![](/_media/dante-controller.png ':size=80%')

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
![](/_media/presets-folder.png)

<!-- div:left-panel -->
2. In Dante Controller, click the :file_folder: **Load a Preset** button.

<!-- div:right-panel -->
![](/_media/load-preset-2.png)

<!-- div:left-panel -->
3. Sometimes the file browser dialog isn’t in the right folder. To get it to the Dante Presets folder, drag it from your Desktop into the dropdown bar at the top of the window.
<br/><br/> Then you can open a preset file.

<!-- div:right-panel -->
![](/_media/load-preset-3.png)

<!-- panels:end -->

## The Default Preset

When you log in to any computer connected to the Dante network, a **Dante Presets** folder will be placed on your Desktop. For nearly all use cases, the Default Preset should suffice. We prefer that you do temporary patches through the patch bay rather than with Dante, unless you need to create something that is repeatable.

Below are all the routings for the Default Preset

### Davis: Mac Pro (via RedNet PCIe)

<!-- tabs:start -->

#### **Inputs**

- **1-10**: From RedNet 2 #3 *INPUT* **7-16**

<details>
<summary>View Table</summary>

| Source Device | Source Channel | RedNet PCIe Channel |
| --- | --- | --- |
| RedNet 2 #3 | 1 | 7 |
| RedNet 2 #3 | 2 | 8 |
| RedNet 2 #3 | 3 | 9 |
| RedNet 2 #3 | 4 | 10 |
| RedNet 2 #3 | 5 | 11 |
| RedNet 2 #3 | 6 | 12 |
| RedNet 2 #3 | 7 | 13 |
| RedNet 2 #3 | 8 | 14 |
| RedNet 2 #3 | 9 | 15 |
| RedNet 2 #3 | 10 | 16 |

</details>

#### **Outputs**

- **1-2**: Stereo out to Roland M-5000 **1-2**
- **3-25**: To *Davis Ambisonic System*

<details>
<summary>View Table</summary>

| RedNet PCIe Channel | Destination Device | Destination Channel |
| --- | --- | --- |
| 1 | Roland M-5000 | 1 |
| 2 | Roland M-5000 | 2 |
| --- | --- | --- |
| 3 | Ambisonic System (via RedNet 2 #2) | 1 |
| 4 | Ambisonic System (via RedNet 2 #2) | 2 |
| 5 | Ambisonic System (via RedNet 2 #2) | 3 |
| 6 | Ambisonic System (via RedNet 2 #2) | 4 |
| 7 | Ambisonic System (via RedNet 2 #2) | 5 |
| 8 | Ambisonic System (via RedNet 2 #2) | 6 |
| 9 | Ambisonic System (via RedNet 2 #2) | 7 |
| 10 | Ambisonic System (via RedNet 2 #2) | 8 |
| 11 | Ambisonic System (via RedNet 2 #2) | 9 |
| 12 | Ambisonic System (via RedNet 2 #2) | 10 |
| 13 | Ambisonic System (via RedNet 2 #2) | 11 |
| 14 | Ambisonic System (via RedNet 2 #2) | 12 |
| 15 | Ambisonic System (via RedNet 2 #2) | 13 |
| 16 | Ambisonic System (via RedNet 2 #2) | 14 |
| 17 | Ambisonic System (via RedNet 2 #2) | 15 |
| 18 | Ambisonic System (via RedNet 2 #2) | 16 |
| 19 | Ambisonic System (via RedNet 2 #3) | 1 |
| 20 | Ambisonic System (via RedNet 2 #3) | 2 |
| 21 | Ambisonic System (via RedNet 2 #3) | 3 |
| 22 | Ambisonic System (via RedNet 2 #3) | 4 |
| 23 | Ambisonic System (via RedNet 2 #3) | 5 |
| 24 | Ambisonic System (via RedNet 2 #3) | 6 |
| 25 | Ambisonic System (via RedNet 2 #3) | 7 |

</details>

<!-- tabs:end -->

### Davis: Roland M-5000

<!-- tabs:start -->

#### **Inputs**

- **1-2**: Stereo in from Mac Pro
- **3-18**: From RedNet 2 #1 *INPUT* **1-16**
- **19-34**: From RedNet 2 #2 *INPUT* **1-16**
- **35-40**: From RedNet 2 #3 *INPUT* **1-6**
- **41-48**: From RedNet MP8R #1 **1-8**
- **49-56**: From RedNet MP8R #2 **1-8**
- **57-64**: From RedNet MP8R #3 **1-8**

<details>
<summary>View Table</summary>

| Source Device | Source Channel | Roland M-5000 *Dante* Channel |
| --- | --- | --- |
| Davis Mac Pro | 1 | 1 |
| Davis Mac Pro | 2 | 2 |
| --- | --- | --- |
| RedNet 2 #1 | 1 | 3 |
| RedNet 2 #1 | 2 | 4 |
| RedNet 2 #1 | 3 | 5 |
| RedNet 2 #1 | 4 | 6 |
| RedNet 2 #1 | 5 | 7 |
| RedNet 2 #1 | 6 | 8 |
| RedNet 2 #1 | 7 | 9 |
| RedNet 2 #1 | 8 | 10 |
| RedNet 2 #1 | 9 | 11 |
| RedNet 2 #1 | 10 | 12 |
| RedNet 2 #1 | 11 | 13 |
| RedNet 2 #1 | 12 | 14 |
| RedNet 2 #1 | 13 | 15 |
| RedNet 2 #1 | 14 | 16 |
| RedNet 2 #1 | 15 | 17 |
| RedNet 2 #1 | 16 | 18 |
| --- | --- | --- |
| RedNet 2 #2 | 1 | 19 |
| RedNet 2 #2 | 2 | 20 |
| RedNet 2 #2 | 3 | 21 |
| RedNet 2 #2 | 4 | 22 |
| RedNet 2 #2 | 5 | 23 |
| RedNet 2 #2 | 6 | 24 |
| RedNet 2 #2 | 7 | 25 |
| RedNet 2 #2 | 8 | 26 |
| RedNet 2 #2 | 9 | 27 |
| RedNet 2 #2 | 10 | 28 |
| RedNet 2 #2 | 11 | 29 |
| RedNet 2 #2 | 12 | 30 |
| RedNet 2 #2 | 13 | 31 |
| RedNet 2 #2 | 14 | 32 |
| RedNet 2 #2 | 15 | 33 |
| RedNet 2 #2 | 16 | 34 |
| --- | --- | --- |
| RedNet 2 #3 | 1 | 35 |
| RedNet 2 #3 | 2 | 36 |
| RedNet 2 #3 | 3 | 37 |
| RedNet 2 #3 | 4 | 38 |
| RedNet 2 #3 | 5 | 39 |
| RedNet 2 #3 | 6 | 40 |
| --- | --- | --- |
| RedNet MP8R #1 | 1 | 41 |
| RedNet MP8R #1 | 2 | 42 |
| RedNet MP8R #1 | 3 | 43 |
| RedNet MP8R #1 | 4 | 44 |
| RedNet MP8R #1 | 5 | 45 |
| RedNet MP8R #1 | 6 | 46 |
| RedNet MP8R #1 | 7 | 47 |
| RedNet MP8R #1 | 8 | 48 |
| --- | --- | --- |
| RedNet MP8R #2 | 1 | 49 |
| RedNet MP8R #2 | 2 | 50 |
| RedNet MP8R #2 | 3 | 51 |
| RedNet MP8R #2 | 4 | 52 |
| RedNet MP8R #2 | 5 | 53 |
| RedNet MP8R #2 | 6 | 54 |
| RedNet MP8R #2 | 7 | 55 |
| RedNet MP8R #2 | 8 | 56 |
| --- | --- | --- |
| RedNet MP8R #3 | 1 | 57 |
| RedNet MP8R #3 | 2 | 58 |
| RedNet MP8R #3 | 3 | 59 |
| RedNet MP8R #3 | 4 | 60 |
| RedNet MP8R #3 | 5 | 61 |
| RedNet MP8R #3 | 6 | 62 |
| RedNet MP8R #3 | 7 | 63 |
| RedNet MP8R #3 | 8 | 64 |


</details>

#### **Outputs**

- **1-16**: To *Davis surround system*
- **17-26**: To RedNet 2 #3 *OUTPUT* **7-16**

<details>
<summary>View Table</summary>

| Roland M-5000 Channel | Destination Device | Destination Channel |
| --- | --- | --- |
| 1 | Davis Surround System (via RedNet 2 #1) | 1 |
| 2 | Davis Surround System (via RedNet 2 #1) | 2 |
| 3 | Davis Surround System (via RedNet 2 #1) | 3 |
| 4 | Davis Surround System (via RedNet 2 #1) | 4 |
| 5 | Davis Surround System (via RedNet 2 #1) | 5 |
| 6 | Davis Surround System (via RedNet 2 #1) | 6 |
| 7 | Davis Surround System (via RedNet 2 #1) | 7 |
| 8 | Davis Surround System (via RedNet 2 #1) | 8 |
| 9 | Davis Surround System (via RedNet 2 #1) | 9 |
| 10 | Davis Surround System (via RedNet 2 #1) | 10 |
| 11 | Davis Surround System (via RedNet 2 #1) | 11 |
| 12 | Davis Surround System (via RedNet 2 #1) | 12 |
| 13 | Davis Surround System (via RedNet 2 #1) | 13 |
| 14 | Davis Surround System (via RedNet 2 #1) | 14 |
| 15 | Davis Surround System (via RedNet 2 #1) | 15 |
| 16 | Davis Surround System (via RedNet 2 #1) | 16 |
| --- | --- | --- |
| 17 | RedNet 2 #3 | 7 |
| 18 | RedNet 2 #3 | 8 |
| 19 | RedNet 2 #3 | 9 |
| 20 | RedNet 2 #3 | 10 |
| 21 | RedNet 2 #3 | 11 |
| 22 | RedNet 2 #3 | 12 |
| 23 | RedNet 2 #3 | 13 |
| 24 | RedNet 2 #3 | 14 |
| 25 | RedNet 2 #3 | 15 |
| 26 | RedNet 2 #3 | 16 |

</details>

<!-- tabs:end -->

## Creating "safe" presets

By default when you create a preset in Dante Controller, it creates a full-system preset with every parameter. This is undesirable because it means when you load the preset it will change every setting for every device on the network. This not only takes a long time, but it can potentially be extremely disruptive. Hence we ask that you create "safe presets" by only selecting the devices and parameters you need for the preset to work.

<!-- panels:start -->

<!-- div:left-panel -->

1. Set your Dante subscriptions

<!-- div:right-panel -->

![](/_media/dante-controller.png 'Setting subscriptions in Dante Controller')

<!-- div:title-panel -->

2. Click the :star: **Save Preset** button

<!-- div:left-panel -->

3. Click "Advanced"

<!-- div:right-panel -->

![](/_media/safe-presets-2.png 'Click the "Advanced" button')

<!-- div:left-panel -->

4. Click the "None" button. Hold down the <kbd>⌘ Command</kbd> key (Use <kbd>Ctrl</kbd> on Windows) and click on the devices you are using.

<!-- div:right-panel -->

![](/_media/safe-presets-3.png 'Select the devices you are using')

<!-- div:left-panel -->

5. Uncheck everything except:

- Sample rate
- Tx Channel Labels *(if you labeled any channels)*
- Tx Flows
- Rx Channel Names *(if you labeled any channels)*
- Rx Channel Subscriptions

Then click save

<!-- div:right-panel -->

![](/_media/safe-presets-4.png 'Select relevant parameters for the preset')

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

![](/_media/rednet-control-2.png)

<!-- panels:end -->

### RedNet 2

<!-- panels:start -->

<!-- div:left-panel -->

The RedNet 2 is a 16x16 (16 in, 16 out) Dante audio interface. This device acts as the bridge between the Dante network and the physical world, allowing audio to be fed in and out of the Dante network.

The [Machine Room][machine-room] has three RedNet 2s. All the I/O for the RedNet 2s is exposed in the Tie Line patch bay.

<!-- div:right-panel -->

![](/_media/rednet-2.png)

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
![](/_media/mp8r-1.png)

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
![](/_media/mp8r-2.png)

<!-- panels:end -->

<!-- tabs:end -->

#### Saving an MP8R preset

If you want to save your channel settings, in the menu bar go to **File > Device Save** and select which devices you want included in the preset. You can load the preset by simply opening the file it creates.