# GNS3_Practice
A simple network pratice with GNS3 and virtualization

To run this practice, you'll need to create a virtual network that can access your real network, 
on Windows you can simply download the loopback driver and make the wifi interface accept an interaction with the loopback (In case of localhost error, try to access cmd 
and run the follow command: .

Auxiliary video: https://www.youtube.com/watch?v=01AeGKoiRtw

In this project I'm using RouterOS from Mikrotik to make my network, to run Mikrotik on GNS3 you'll need the Qemu software installed in your machine and then 
import the OS on GNS3. Here's the techonologies used: 
- [GNS3](https://www.gns3.com/software/download/)
- [QEMU](https://www.qemu.org/download/)
- [RouterOS](https://mikrotik.com/download)

## Next Steps:
- Implement firewall on the network;
- Create a small simulated provider;
- Automate some settings with Python





