<!-- Document links. Please put all links here to make broken link checking easier. -->
[av-panels]: /av-panels.md
[clearcom]: /clearcom.md
[control-room]: /control-room.md
[dante]: /dante.md
[edit-rooms]: /edit-rooms.md
[lan]: /lan.md
[machine-room]: /machine-room.md
[mtl]: /mtl.md
[davis]: /davis-studio.md
[video-switcher]: /video-switcher.md
[workshop]: /workshop.md
[helpdesk]: https://sites.google.com/umich.edu/pat/helpdesk
[training]: https://sites.google.com/umich.edu/pat/training
[slack]: http://um-smtd-tech-suite.slack.com
[studio-log]: https://airtable.com/shr7JLVvBXZWAFSaD

[motu-drivers]: https://motu.com/en-us/download/

[mac-audio-settings]: https://support.apple.com/guide/mac-help/quickly-change-settings-mchl50f94f8f/mac
[windows-audio-settings]: https://www.makeuseof.com/windows-11-change-sound-output-device/
[ableton-audio-settings]: https://help.ableton.com/hc/en-us/articles/211476789-Setting-up-an-Audio-Interface
[logic-audio-settings]: https://support.apple.com/guide/logicpro/devices-settings-lgcpbb81aca5/10.7.5/mac/12.3
[protools-audio-settings]: https://obedia.com/how-to-setup-an-audio-interface-in-pro-tools/
[reaper-audio-settings]: https://slatedigital.zendesk.com/hc/en-us/articles/360008932653-Reaper-I-O-Settings

# The Edit Rooms <small>*Moore 378A / 378B*</small>
?> The Edit Rooms require the completion of the [Tech Suite Orientation][training] to use.

The Edit Rooms are essentially more advanced versions of the MTL stations. They can be used for recording, mixing, mastering, and more!

Each Edit Room has a different set of studio monitor speakers so you can listen to your work using real reference speakers. The two different models of speakers allows you compare and contrast on different setups. Instead of the red Scarlett audio interface, the Edit Rooms are equipped with a larger Audient EVO 16. Each Edit Room has a dynamic and condenser microphone.

For more advanced users, the Edit Rooms computers connected to the [Dante][dante] network and the Tech Suite [video switcher][video-switcher]. Both rooms also have an [AV panel][av-panels]. This means they can be used as isolation booths in conjunction with the [Control Room][control-room]. The can be used as remote mixing/recording/control stations for performances in [Davis][davis], Hankinson, Watkins, and MacIntosh. Submit a [Helpdesk Ticket][helpdesk] for assistance on setting up these advanced configurations.

<!-- TODO: More Images -->

## Known Issues

**Found an urgent issue?** Submit a [Helpdesk Ticket][helpdesk].

<iframe class="airtable-embed" src="https://airtable.com/embed/shrHT0QKyoIv3xwif?backgroundColor=blue" frameborder="0" onmousewheel="" width="100%" height="600px" style="background: transparent; border: 1px solid #ccc;"></iframe>

## Equipment Overview
?> Links go to item manuals

?> You are welcome to tinker with the Arturia MiniBrute 2 but we will not be covering it in this manual.

<!-- tabs:start -->

### **Simple**
- iMac
- TV Screen
- Dynamic Microphone
- Condenser Microphone
- Audio Interface (EVO 16)
- [Ableton Push 2](https://www.ableton.com/en/push/learn-push/) Controller
- [Arturia MiniBrute 2S](https://www.arturia.com/minibrute-2s/resources) Step Sequencing Analog Synth
- MIDI Keyboard Controller
- Studio Monitors
- Subwoofer

### **With Make/Model**
- iMac
- TV Screen
- Dynamic Microphone + cable + stand — *Shure BETA 58A*
- Condenser Microphone + cable + stand — *Audio Technica AT2020*
- Audio Interface — *Audient EVO 16*
- [Ableton Push 2](https://www.ableton.com/en/push/learn-push/) Controller
- [Arturia MiniBrute 2S](https://www.arturia.com/minibrute-2s/resources) Step Sequencing Analog Synth

#### Edit Room A
- MIDI Keyboard Controller — *[M-audio Code 61](https://m-audio.com/support/documents-search)*
- Studio Monitors — *Neumann _*
- Subwoofer — *Neumann _*

#### Edit Room B
- MIDI Keyboard Controller — *[Novation Impulse 61](https://downloads.novationmusic.com/novation/impulse/impulse-61)*
- Studio Monitors — *Dynaudio _*
- Subwoofer — *Dynaudio _*

<!-- tabs:end -->

## Turning the room on/off
<!-- panels:start -->

<!-- div:left-panel -->
The Edit Rooms use a sequenced power switch. All you need to do is tilt the switch labeled **Power Button** towards the **On** or **Off** position (it will not stay there, its only a momentary switch). Just wait for all the status lights to light up orange.

!> Always turn the power off when you are done!

<!-- div:right-panel -->
![](/_media/er-rack.webp)

<!-- panels:end -->

## Using your own laptop
![](/_media/er-usb.webp ':size=50%')

To use your own computer with the audio interface, all you need to do is plug in the USB connector provided and hit the button USB switcher button until **2** is illuminated.

This will allow you to use the audio interface, MIDI keyboard, and Ableton Push with your own laptop. It will also license any software stored on our iLok license USB, if you have iLok and the respective software installed.

## Audio Output

<!-- panels:start -->

<!-- div:left-panel -->
1. Check the USB switcher.

- Make sure **1** is chosen if you are using the iMac
- Make sure **2** is chosen if you are using your own computer. You may need to [install drivers](https://evo.audio/products/audio-interfaces/evo-16/downloads/) to make it work.

<!-- div:right-panel -->
![](/_media/er-usb.webp)

<!-- div:left-panel -->
2. Make sure the computer's output is set to **EVO 16**

- On a Mac, you can use ![](/_media/control-center.webp ':no-zoom :size=30px') [Control Center][mac-audio-settings] as shown on the right.
- On Windows, open your [sound settings][windows-audio-settings] from the taskbar. 
- In a DAW you may need to change the output settings
    - [Ableton][ableton-audio-settings]
    - [Logic][logic-audio-settings]
    - [Pro Tools][protools-audio-settings]
    - [Reaper][reaper-audio-settings]

> If you had to change the USB switcher in step 1, it may take around 10 seconds for the EVO 16 to show up in the audio devices.

<!-- div:right-panel -->
![](/_media/control-center-1.webp)

<!-- div:left-panel -->
3. On the EVO 16, select the monitor **(10)** button and turn up the main control knob **(9)**

> You can also plug in headphones **(3)** and control the volume **(9)** of each channel in the same way as the monitor using the corresponding numbered button **(12)**

<!-- div:right-panel -->
![](/_media/evo16.webp)

<!-- panels:end -->

## Microphones

<!-- panels:start -->

<!-- div:left-panel -->
- Both mics are equipped with pop guards. Please be gentle with the pop guard on the condenser as it is fragile.
- The condenser mic requires phantom power to use (see [audio input](#audio-input) guide below)
- Each mic has a corresponding blue XLR cable that should be coiled (over-under!) neatly and hung up after each session, as shown

<!-- div:right-panel -->
![](/_media/er-mics.webp 'The condenser (AT2020) is on the left and the dynamic (BETA 58A) is on the right.')

<!-- panels:end -->


## Audio Input

<!-- panels:start -->

<!-- div:left-panel -->

- To control input gain on the EVO, hit the numbered button corresponding to your channel number and rotate the main control knob **(9)**
- The condenser mic (the AT2020) requires phantom power! To turn on phantom power, hit the numbered button corresponding to your channel number and hit the <kbd>48V</kbd> **(7)** button.
- Some line-level instruments like guitars require additional amplification. To turn on instrument mode for a channel, hit the numbered button corresponding to your channel number and hit the guitar **(8)** button.
- See the quick start guide to learn more about the EVO 16's smart gain feature

To learn more about how to use the EVO 16, follow this [quick start guide](https://d9w4fhj63j193.cloudfront.net/EVO/EVO%2016/EVO%2016%20Quick%20Start%20Guide%20V1%20(Web%20Version).pdf) or [flip through the manual](https://d9w4fhj63j193.cloudfront.net/2022/EVO%2016/6.%20User%20Guide/EVO%2016%20Manual%20V2.2.pdf)

<!-- div:right-panel -->
![](/_media/evo16.webp)

<!-- panels:end -->

## Using the TV
The TV is controlled using the provided TV remote. **DON'T LOSE IT!** Put it back on top of the rack when you aren't using it.

- HDMI 1 is the video switcher, if you know how to use it
- HDMI 2 is the computer so you can use the TV as a second monitor

Make sure to turn it off when you are done.

## Zero Setting

- <input type="checkbox"> Turn off the rack
- <input type="checkbox"> Log out
- <input type="checkbox"> Push the chairs in
- <input type="checkbox"> Coil up (using over-under!) and hang blue XLR cables
- <input type="checkbox"> Put the mics off to the side of the room out of the way
- <input type="checkbox"> Fill out the studio log
- <input type="checkbox"> Take all your personal belongings with you

> Please leave the computer on so it can perform updates overnight

## Troubleshooting tips
- Remember to check the [known issues list](#known-issues)
- If the EVO 16 doesn't connect:
    1. Try turning the rack off and on again
    2. Restart the computer
    3. Make sure you have the latest version of the EVO 16 driver

> If you continue to have issues or your issue isn't listed here, [include it in your Studio Log][studio-log] or submit a [Helpdesk Ticket][helpdesk] if its an urgent issue.