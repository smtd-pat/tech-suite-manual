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

# The Tech Suite LAN

<details>
<summary>What is a LAN?</summary>

> A LAN, or Local Area Network, is a computer network. Just like the internet, it connects lots of computers and other devices together. Unlike the internet, a LAN is a small private network usually with only a handful of devices on it. Devices can be connected to a LAN and the internet at the same time. Some LANs can be connected to wirelessly, however our network can only be connected to via ethernet.
</details>

The Tech Suite LAN is primarily used to connect the Tech Suite's [Dante][dante] devices together. The LAN uses a hub-and-spoke model, with two Cisco ethernet switches in the [Machine Room][machine-room] acting as the hub.

The Tech Suite LAN also carries the web interface that is used to control the [SDI video switcher in the Machine Room][video-switcher].

> Users are discouraged from using the LAN for high-bandwidth protocols like UDP and video streaming, as it could interfere with the Dante network. However, devices can be connected directly or connected to their own separate ethernet switch and/or router via the [machine room patch bay][machine-room].