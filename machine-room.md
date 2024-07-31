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
[helpdesk]: https://pat.smtd.umich.edu/helpdesk
[training]: https://pat.smtd.umich.edu/training

# The Machine Room <small>*Moore 372*</small>
?> The Machine Room requires a [certification][training] to use.

The machine room is the heart of the Tech Suite, and arguably, the heart of the entire Moore building. The machine room features patch bays to route all [AV panels][av-panels] and equipment throughout the building, as well as playing host to some of the primary Dante network audio equipment used throughout the building.

The switches for the [Tech Suite LAN][lan] are also located in the Machine Room.

<!-- TODO: More Images -->

## Known Issues

**Found an urgent issue?** Submit a [Helpdesk Ticket][helpdesk].

<iframe class="airtable-embed" src="https://airtable.com/embed/shrxNqE7lInLejewY?backgroundColor=blue" frameborder="0" onmousewheel="" width="100%" height="600px" style="background: transparent; border: 1px solid #ccc;"></iframe>

## Equipment Overview

?> ITS Networking Equipment is not included in this inventory

- 64 port longframe patch bays x3
- 12 port XLRP patch bays x6
- 12 port XLRS patch bays x4
- ListenUp LT-800 FM Transmitter
- Focusrite RedNet MP8R Mic Preamp x3
- Focusrite RedNet 2 x3 
- Cisco SG300-28PP 28-port Gigabit PoE+ Managed Switch x2
- 48 port Belden Rack Mount RJ45 Cat6 Patch Panel x2
- AJA Kumo 1616 3G SDI Router
- 52 port SDI patch panels x2
- Tripp-Lite 16 port fiber patch panel
- Clear-Com Encore PS-702
- Sonifex Redbox
- Apogee Big Ben Master Digital Clock

## Zero Setting
When you are done with the Machine Room, please ensure the following
- Remove all patch cables that aren't green or black.
- Ensure all additional cables are coiled cleanly and stored in their proper place
- Ensure all dongles, adapters, and devices are stored in the proper place
- Load the default preset
Reset the MP8R channel settings back to their initial values (gain 0, all - settings off)

## Cable Storage
Nearly all cables in the Tech Suite are stored in the Machine Room.
- All XLR, TRS, HDMI, and ethernet cables should be warped in a roughly 1ft coil with both connectors secured together by the cable tie. No dangling connectors!
- All shelves, bins, and pegs have a label designating what should go on them.
Long pigtails should be folded in half twice, tied in a loose knot, and hung on their designated peg.
- Different color cable ties indicate different lengths.
    - :blue_heart: Blue for 10ft
    - :green_heart: Green for 25ft
    - :heart: Red for 50ft.

## Tie Line Patch Bay

![A 48-port Longframe patch bay](/_media/patch-bay.webp ':size=80%')

Tie lines can be used to route line level audio to and from the RedNet 2 Dante audio interfaces or to another AV panel.

!> Do not use ¼” connectors with the tie line patch bay. The tie line patch bay only uses Longframe/B-Gauge/Bantam/TT connectors. These are not the same as ¼” TS/TRS connectors. <br/><br/> ![The difference between a typical quarter inch TRS cable and a Longframe patch cable](/_media/dont-use-trs.webp ':size=150px')

> Please reset all patch bay connections to their default settings after use

> This patch bay does not prevent you from doing stupid things like patching outputs to outputs or inputs to inputs. Please don't do this. 

### Cables
Cables come in three colors. While all cables are functionally the same, we can use color to indicate the purpose or signal type of the cable. Our current system is as follows:
- :heart: Red for all temporary patches
- :black_circle: Black for Davis surround system speaker output **(do not use for other purposes or remove)**
- :green_heart: Green for Davis Ambisonic system speaker output **(do not use for other purposes or remove)**

### Tips
- All connections are [non-normalled](https://www.sweetwater.com/insync/non-normalled/)
- A tie line can be patched to any other tie line. *However* you must ensure that your signal is flowing in the correct direction or you will risk damaging equipment connected to the patch. Do not patch 2 transmitter devices or 2 receiver devices together. Your signal should always flow from a transmitter to a receiver.
- All active tie line ports on the patch bays are labeled with their location and/or device.
- Tie lines can be connected directly together
- Tie lines can be patched into a Dante audio interface via our three Focusrite RedNet 2 racks, which respectively have their 8 inputs and outputs exposed on the patch bay.
- **Troubleshooting Tip:** Push hard when plugging in Longframe cables, as occasionally they will not plug all the way in and cause mysterious audio problems.

!> Always turn speakers off before patching

## Microphone Patch Bays
Microphones can be patched using blue XLR patch cables. Microphones almost always go into our Focusrite RedNet MP8R mic preamplifiers exposed on the patch bay. These racks are controlled via a piece of software called [RedNet Control 2][dante]. Microphone lines can also be routed to the Control Room.

### Tips
- Microphones can be patched using blue XLR patch cables.
- XLR Racks 1-6 (labeled MR. MP#) are outputs, indicated by the XLRP connectors. All ports are labeled with their source location and ID
- XLR Racks 7-10 (labeled MR. MP#) are inputs, indicated by the XLRS connectors. All ports are labeled with their destination and ID.
- CTRL RM 1-8 are tie lines to the control room storage closet patch bay
- All MP8R ports go to the Focusrite RedNet MP86 Mic Preamp racks below the patch bay.

!> Always turn speakers off before patching

## AV Data Patch Bay
The AV Data patch bay is just a bunch of ethernet/RJ45 ports. They are agnostic to what you use them for. If you just need to make a peer to peer (P2P) connection to another device, you can to connect two AV ports directly together. However, normally you are going to want to connect to the [Tech Suite LAN][lan]. To do that, you can plug into any of the open ports on the two Cisco ethernet switches above the AV data patchbay.

?> You can use this patch bay to patch your personal computer into the [Tech Suite LAN][lan] which will allow you to use [Dante Virtual Soundcard][dante] (if you have it), [Dante Controller][dante], and [RedNet Control 2][dante].

!> **Do not remove Black Cables** as they go to equipment that is always plugged in


### Tips
- All RJ45 ports are labeled with their AV Panel location and ID.

## SDI Patch Bay
The SDI patch bay can be used to route any SDI connection between AV panels or to the [AJA Kumo SDI switcher][video-switcher].

## Other patch bays
The **multimode fiber** patch bay can be used to route fiber devices, however this is a seldom used connection in the Tech Suite.

The **internet** patch bay at the top of the right-side rack is ITS equipment and should not be modified under any circumstances. There are plenty of ethernet connections throughout the studios and hence no need to patch internet into the AV panels.