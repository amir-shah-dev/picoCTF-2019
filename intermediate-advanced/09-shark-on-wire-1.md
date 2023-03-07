# shark on wire 1
## Objectives
> - Knowing how to inspect .pcap files using Wireshark.

To complete this challenge we are going to need a packet capture inspector program such as Wireshark (which can be downloaded from My IT Shop!). In it we can open the .pcap file we’ve downloaded from the challenge. 
<details>
<summary>Hint</summary>
<br>
Now this is the hard part, as we are looking for a needle in a haystack. For starters let’s click on the magnifying glass icon (Find a packet), which will bring up a new bar. We’ll set the filter to ‘String’ and change the leftmost field to ‘Packet bytes’. Then, taking advantage of the fact we know the flag format, we’ll search for ‘pico’, which will bring up Frame 55. If we right click it, click on Follow and then UDP stream, we will see the text ‘picopicopicopico’, so this was a trap! However, not all hope is lost, as close to this frames we find some other ones of 1 byte of length, which is odd (make sure your display filter is empty after the previous step to see this). Following the stream on that first length 1 frame gives us the flag (note that only the frames directed towards 10.0.0.12 contain the flag, the others contain either useless information or a false flag).
</details>