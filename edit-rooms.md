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
[helpdesk]: https://pat.smtd.umich.edu/helpdesk
[training]: https://pat.smtd.umich.edu/training
[studio-log]: https://pat.smtd.umich.edu/studiolog

# The Edit Rooms <small>*Moore 378A / 378B*</small>
?> The Edit Rooms require the completion of the [Tech Suite Orientation][training] to use.

The Edit Rooms are essentially more advanced versions of the MTL stations. They can be used for recording, mixing, mastering, and more!

Each Edit Room has a different set of studio monitor speakers so you can listen to your work using real reference speakers. The two different models of speakers allows you compare and contrast on different setups. The Edit Rooms have a larger audio interface that allows for more inputs and outputs than the MTL. Each Edit Room has a dynamic and condenser microphone.

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
- Mac Studio
- 4K Monitor *x2*
- Dynamic Microphone
- Condenser Microphone
- Audio Interface
- [Ableton Push 2](https://www.ableton.com/en/push/learn-push/) Controller
- [Arturia MiniBrute 2S](https://www.arturia.com/minibrute-2s/resources) Step Sequencing Analog Synth
- MIDI Keyboard Controller
- Studio Monitors
- Subwoofer

### **With Make/Model**
- Mac Studio (M2 Max, 64 GB Memory)
- ASUS ProArt PA320CRV 4K Monitor *x2*
- Shure BETA 58A Dynamic Microphone
- Audio Technica AT2020 Condenser Microphone
- Tascam US-16x08 Audio Interface
- [Ableton Push 2](https://www.ableton.com/en/push/learn-push/) Controller
- [Arturia MiniBrute 2S](https://www.arturia.com/minibrute-2s/resources) Step Sequencing Analog Synth

#### Edit Room A
- MIDI Keyboard Controller — *[M-audio Code 61](https://m-audio.com/support/documents-search)*
- Studio Monitors — *Neumann KH120A*
- Subwoofer — *Neumann KH 805*

#### Edit Room B
- MIDI Keyboard Controller — *[Novation Impulse 61](https://downloads.novationmusic.com/novation/impulse/impulse-61)*
- Studio Monitors — *Dynaudio BM6 mkIII*
- Subwoofer — *Dynaudio BM6S II*

<!-- tabs:end -->

## Using your own laptop
![](/_media/er-usb.webp ':size=50%')

To use your own computer with the audio interface, all you need to do is plug in the USB connector provided and hit the button USB switcher button until **2** is illuminated.

This will allow you to use the audio interface, MIDI keyboard, and Ableton Push with your own laptop. It will also license any software stored on our iLok license USB, if you have iLok and the respective software installed.

## Audio Output

<!-- panels:start -->

<!-- div:left-panel -->
1. Check the USB switcher.

- Make sure **1** is chosen if you are using the Mac Studio
- Make sure **2** is chosen if you are using your own computer
    - Windows users will need to [install drivers](https://asio4all.org/about/download-asio4all/). Make sure to include the offline settings in the installer.

<!-- div:right-panel -->
![](/_media/er-usb.webp)

<!-- div:left-panel -->
2. Make sure the computer's output is set to **US-16x08**

- On a Mac, you can use ![](/_media/sw-control-center.webp ':no-zoom :size=30px') [Control Center](https://support.apple.com/guide/mac-help/quickly-change-settings-mchl50f94f8f/mac) as shown on the right.
- On Windows, open your [sound settings](https://www.makeuseof.com/windows-11-change-sound-output-device/) from the taskbar. 
- In a DAW you may need to change the output settings
    - [Ableton](https://help.ableton.com/hc/en-us/articles/211476789-Setting-up-an-Audio-Interface)
    - [Logic](https://support.apple.com/guide/logicpro/devices-settings-lgcpbb81aca5/10.7.5/mac/12.3)
    - [Pro Tools](https://obedia.com/how-to-setup-an-audio-interface-in-pro-tools/)
    - [Reaper](https://slatedigital.zendesk.com/hc/en-us/articles/360008932653-Reaper-I-O-Settings)

<!-- div:right-panel -->
![](/_media/sw-control-center-1.webp)

<!-- div:left-panel -->
3. On the audio interface, turn up the **Line Out 1-2** knob.

<!-- div:right-panel -->
![](/_media/er-interface-lineout.webp)

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
Audio input is as simple as plugging in the device you wish to record with and setting the gain using the respective knob for that input. If your microphone needs **phantom power**, use the switches on the left to turn it on.

If you are using input 9 or 10, you can switch between **LINE** and **INST** or instrument. **Line** is good for most electronic instruments like synths, while **inst** is best used with instruments that have pickups like electric guitars or basses. If you can't hear your instrument on one setting, try the other.

> Its ok to have phantom power turned on for channels that do not require it. Almost all modern microphones and XLR line-in devices will safely ignore phantom power.

<!-- div:right-panel -->
![](/_media/er-interface.webp)

<!-- panels:end -->

## Using the video switcher
The top computer monitor is also hooked up to the the [Video Switcher](video-switcher) which can be used to view the cameras in the Davis Studio, Hankinson, Watkins, Britton, and MacIntosh. Switch the top monitor to HDMI 2 to use the video switcher. 

## Zero Setting
- <input type="checkbox"> Log out
- <input type="checkbox"> Push the chairs in
- <input type="checkbox"> Coil up (using over-under!) and hang yellow XLR cables
- <input type="checkbox"> Put the mics off to the side of the room and make sure they aren't blocking the door
- <input type="checkbox"> Fill out the studio log
- <input type="checkbox"> Take all your personal belongings with you

> Please leave the computer on so it can perform updates overnight

## Troubleshooting tips
- Remember to check the [known issues list](#known-issues)

> If you continue to have issues or your issue isn't listed here, [include it in your Studio Log][studio-log] or submit a [Helpdesk Ticket][helpdesk] if its an urgent issue.