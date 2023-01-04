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
[policies]: https://sites.google.com/umich.edu/pat/tech-suite/policies
[slack]: http://um-smtd-tech-suite.slack.com
[studio-log]: https://airtable.com/shr7JLVvBXZWAFSaD
[smtd-it]: https://smtd.umich.edu/intranet-portal/it-resources/

[learn-live]: https://www.ableton.com/en/live/learn-live/
[learn-push]: https://www.ableton.com/en/push/learn-push/
[novation-manual]: https://fael-downloads-prod.focusrite.com/customer/prod/s3fs-public/novation/downloads/25432/english107.pdf
[mac-audio-settings]: https://support.apple.com/guide/mac-help/quickly-change-settings-mchl50f94f8f/mac
[ableton-audio-settings]: https://help.ableton.com/hc/en-us/articles/211476789-Setting-up-an-Audio-Interface
[logic-audio-settings]: https://support.apple.com/guide/logicpro/devices-settings-lgcpbb81aca5/10.7.5/mac/12.3
[protools-audio-settings]: https://obedia.com/how-to-setup-an-audio-interface-in-pro-tools/
[reaper-audio-settings]: https://slatedigital.zendesk.com/hc/en-us/articles/360008932653-Reaper-I-O-Settings

# The Music Technology Lab <small>*Moore 378*</small>
?> The MTL requires the completion of the [Tech Suite Orientation][training] to use.

![](/_media/mtl-station.webp ':size=50%')

The MTL is a classroom space featuring 12 audio workstations. Each workstation features an Ableton Push, a MIDI keyboard, audio interface, and headphone amp.

## Policies

- Please do not unplug and re-route any USB, power, or audio cables from the back any device. If you need to hook things up to your personal computer, please use the Edit Rooms.
- Remember, your files are not safe in the Tech Suite
- Keep your station clean and tidy. Put everything back where you found it when you are done.
- If you use the Ableton Push, please turn it off at the end of your session.

[View the full list of Tech Suite policies here][policies]

## Known Issues

**Found an urgent issue?** Submit a [Helpdesk Ticket][helpdesk].

<iframe class="airtable-embed" src="https://airtable.com/embed/shrHMC2yGOeWWybJg?backgroundColor=blue" frameborder="0" onmousewheel="" width="100%" height="600px" style="background: transparent; border: 1px solid #ccc;"></iframe>

## Equipment Overview

*Each MTL station contains the following items...*

<!-- tabs:start -->

### **Ableton Push 2**
<!-- panels:start -->

<!-- div:left-panel -->
The Ableton Push is made to be used with the software [Ableton Live][learn-live] but is also compatible with some other DAWs.

[Learn how to use][learn-push]

<!-- TODO: Link "DAWs" to terminology page -->

<!-- div:right-panel -->
![](/_media/push.webp)

<!-- panels:end -->

### **Scarlett 8i6**
<!-- panels:start -->

#### Focusrite Scarlett 8i6 (Gen 1)

<!-- div:left-panel -->
This is called an Audio Interface. It allows to to...
- Connect powered and unpowered microphones to your computer
- Connect instruments with pickups, like electric guitars, to your computer
- Play back and route many channels of audio output

<!-- TODO: Link stuff to terminology page -->

It can do all of that and more!

<!-- div:right-panel -->
![](/_media/8i6.webp)

<!-- panels:end -->

### **Rolls Headphone Amp**
<!-- panels:start -->

#### Rolls Headphone Amp (RA35b)

<!-- div:left-panel -->
This is called a headphone amplifier. It also can split audio output to up to five pairs of headphones. While some headphones require amplifiers, all headphones can be used with one. Each headphone channel has a volume knob, a 1/4" TRS jack, and an 1/8" (or aux) jack.

<!-- TODO: Link stuff to terminology page -->

<!-- div:right-panel -->
![](/_media/rolls.webp)

<!-- panels:end -->

### **MIDI Keyboard**
<!-- panels:start -->

#### Novation Keyboard (49SL MkII)

<!-- div:left-panel -->
This is a MIDI keyboard. It can be used to send MIDI piano data into a DAW or other software that supports MIDI. It also has a number of additional controls. What the other controls do varies based on what software you are using and how that software is configured.

[View Manual][novation-manual]

<!-- TODO: Link stuff to terminology page -->

<!-- div:right-panel -->
![](/_media/keyboard.webp)

<!-- panels:end -->

<!-- tabs:end -->

## Getting audio output
<!-- panels:start -->

<!-- div:left-panel -->
Using ![](/_media/control-center.webp ':no-zoom :size=30px') [Control Center][mac-audio-settings] menu in the top-right of the screen, set your system output device to **Scarlett 8i6 USB** as shown on the right.

In a DAW you may need to change the output settings
- [Ableton][ableton-audio-settings]
- [Logic][logic-audio-settings]
- [Pro Tools][protools-audio-settings]
- [Reaper][reaper-audio-settings]

<!-- div:right-panel -->
![](/_media/mtl-audio-1.webp) ![](/_media/mtl-audio-2.webp)

<!-- panels:end -->

## Setting up Ableton


## Using the room speakers

### Turning everything on
!> Always turn things on in this order or you may damage the speakers

<!-- panels:start -->

<!-- div:left-panel -->
1. First turn on the rack power

> *Wait 10 seconds (seriously, wait for everything to turn on)*

<!-- div:right-panel -->
![](/_media/mtl-av-on-1.webp)

<!-- div:left-panel -->
2. Turn on the speakers

<!-- div:right-panel -->
![](/_media/mtl-av-on-2.webp)

<!-- panels:end -->

### Turning everything off
!> Always turn things off in this order or you may damage the speakers

1. Turn off the speakers
2. Turn off the rack power

### Sending audio to the speakers from any workstation
<!-- panels:start -->

<!-- div:left-panel -->
1. *At your workstation:* On the audio interface, turn up the **Monitor** knob all the way down. Note what number your station is.

> Each station has a label on the computer that says "MTL #". That "#" is your station number.

2. *At the AV rack:* Find your station number on one of the blue mixers. Each channel has a front knob (volume) and a back knob (pan). Turn the front knob to about 5.

3. *At your workstation:* Play audio out of the audio interface. Slowly turn up the **Monitor** knob.

!> When you are done, turn down the **Monitor** knob on the audio interface and turn down your station's volume knob on the AV rack. Keep the **Main Out** knob on the top blue mixer turned to 5.

<!-- div:right-panel -->
![](/_media/mtl-av-station-audio.webp)

<!-- panels:end -->

### Audio output from the aux cable
<!-- panels:start -->

<!-- div:left-panel -->
1. Turn the highlighted white knob all the way down
2. Plug in the aux cable
3. Turn up your device to its max volume and start playing audio
4. Slowly turn up the white knob to the desired volume

!> When you are done, turn the volume down before unplugging. Keep the **Main Mix** knob turned to 5.

<!-- div:right-panel -->
![](/_media/mtl-aux.webp)

<!-- panels:end -->

### Audio output from the teaching station computer
1. Turn the white knob labeled **Teaching Station** all the way down. Its directly left of the knob shown above.
2. On the teaching station audio interface, turn up the **Monitor** knob to about 5
3. Play audio out of the audio interface from the teaching station
4. Slowly turn up the white knob labeled **Teaching Station** to the desired volume

!> When you are done, turn the volume back down. Keep the **Main Mix** knob turned to 5.

## Need help?
If you are running into technical problems, [include it in your Studio Log][studio-log] or submit a [Helpdesk Ticket][helpdesk] if its an urgent issue.

Remember to check the [known issues list](#known-issues)

### Live encountered a licensing error
Try relaunching Live. If that doesn't work, please contact [SMTD IT][smtd-it] directly, as they are in charge of the licensing server.