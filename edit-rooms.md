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
[slack]: http://www.google.com/url?q=http%3A%2F%2Fum-smtd-tech-suite.slack.com&sa=D&sntz=1&usg=AOvVaw2gqNoycvIamkVK8pChYGQw
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

Each Edit Room has a different set of studio monitor speakers so you can listen to your work using real reference speakers. The two different models of speakers allows you compare and contrast on different setups. Instead of the red Scarlett audio interface, the Edit Rooms are equipped with a larger MOTU 8M. Each Edit Room has a dynamic and condenser microphone.

For more advanced users, the Edit Rooms computers connected to the [Dante][dante] network and the Tech Suite [video switcher][video-switcher]. Both rooms also have an [AV panel][av-panels]. This means they can be used as isolation booths in conjunction with the [Control Room][control-room]. The can be used as remote mixing/recording/control stations for performances in [Davis][davis], Hankinson, Watkins, and MacIntosh. Reach out on [Slack][slack] or submit a [Helpdesk Ticket][helpdesk] for assistance on setting up these advanced configurations.

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
- Audio Interface (MOTU 8M)
- Monitor Controller (PreSonus)
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
- Audio Interface — *MOTU 8M*
- Monitor Controller — *PreSonus Monitor Station v2*
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
![](/_media/edit-room-1.jpg)

<!-- panels:end -->

## How to get audio output
<!-- panels:start -->

<!-- div:left-panel -->
!> Make sure to turn down the Main knob on the PreSonus Monitor Station first.

<!-- div:right-panel -->
![](/_media/edit-room-2.jpg)

<!-- panels:end -->

<!-- tabs:start -->

### **From Audio Interface**
<!-- panels:start -->

<!-- div:left-panel -->
1. Check the MOTU USB switcher.

- Make sure **Desktop** is chosen if you are using the iMac
- Make sure **Laptop** is chosen if you are using your own computer. You may need to [install drivers][motu-drivers] to make it work.

<!-- div:right-panel -->
![](/_media/edit-room-4.jpg)

<!-- div:left-panel -->
2. Make sure the computer's output is set to **8M**

- On a Mac, you can use ![](/_media/control-center.png ':no-zoom :size=30px') [Control Center][mac-audio-settings] as shown on the right.
- On Windows, open your [sound settings][windows-audio-settings] from the taskbar. 
- In a DAW you may need to change the output settings
    - [Ableton][ableton-audio-settings]
    - [Logic][logic-audio-settings]
    - [Pro Tools][protools-audio-settings]
    - [Reaper][reaper-audio-settings]

> If you had to change the USB switcher in step 1, it may take around 30 seconds for the MOTU to show up in the audio devices. If it doesn't show up, see [troubleshooting tips](#troubleshooting-tips)

<!-- div:right-panel -->
![](/_media/control-center-1.png) ![](/_media/edit-room-3.png)

<!-- div:left-panel -->
3. Press the <kbd>ST1</kbd> button under **Main Source** on the PreSonus Monitor Station

<!-- div:right-panel -->
![](/_media/edit-room-2.jpg)

<!-- div:title-panel -->
4. Play audio and slowly turn up the main knob on the PreSonus to set your volume.

<!-- panels:end -->

### **Aux Audio**
<!-- panels:start -->
<!-- div:title-panel -->
1. Plug in your audio device to the aux cable

<!-- div:left-panel -->
2. Press the <kbd>AUX</kbd> button under **Main Source** on the PreSonus Monitor Station

> Make sure the switch labeled **AUX SPDIF** is unpressed as show in the diagram above the switch

<!-- div:right-panel -->
![](/_media/edit-room-2.jpg)

<!-- div:title-panel -->
3. Turn up your device to its max volume and start playing audio
4. Slowly turn up the main knob on the PreSonus to set your volume.
<!-- panels:end -->

<!-- tabs:end -->

## Using the TV
The TV is controlled using the provided TV remote. **DON'T LOSE IT!** Put it back on top of the rack when you aren't using it.

- HDMI 1 is the video switcher, if you know how to use it
- HDMI 2 is the computer so you can use the TV as a second monitor

Make sure to turn it off when you are done.

## Troubleshooting tips
- If the MOTU doesn't connect:
    1. Try restarting the MOTU using the MOTU's power switch
    2. Restart the computer
    3. Make sure you have the latest version of the MOTU driver

> If you continue to have issues or your issue isn't listed here, [include it in your Studio Log][studio-log] or submit a [Helpdesk Ticket][helpdesk] if its an urgent issue.