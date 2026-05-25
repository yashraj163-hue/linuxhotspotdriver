to be updated with more issue details:

hey everyone,
Recently while trying to update and download a few python libraries in my wsl (windows subsystem linux) I faced an issue. I was using my mobile hotspot to download the packages, which led to a heavy loss of packets probably due to the usage of restricted ipv6 protocol while wsl uses ipv4.
Even when I set the network mode to mirrored and managed the protocols there was a significant loss of packets as follows:

--- google.com ping statistics ---

3 packets transmitted, 1 received, 66.6667% packet loss, time 2015ms
rtt min/avg/max/mdev = 89.097/89.097/89.097/0.000 ms

The temporary fix would be using a wired tethering hotspot. BUT
I am too egoistic to use wires.
I am trying to build a decently working wifi driver for wsl which supports ipv6 and bypasses jio and airtel's bullshit.
Here is my repo link: https://lnkd.in/ge_S8zsA
if any one has experience working with linux your help will be rejoiced by all of us wsl creatures.

<img width="629" height="335" alt="image" src="https://github.com/user-attachments/assets/a3ec82bb-abf0-4c3a-a4b6-f042d9dc61b1" />
