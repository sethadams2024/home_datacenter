I want this as my dedicated device for accessing network equipment. So, I am gonna use SSH and VNC

For vnc, I followed this document
https://www.raspberrypi.com/documentation/computers/remote-access.html#vnc

hit the rasp pi logo on top left and hit preferences:
1. enable SSH
2. enable VNC


a. Download TigerVNC. You can install the latest version from the Releases page of their GitHub repository. Click on the link in the latest release, and find the binary for your platform. Windows users should download an exe; macOS users should download the dmg; Linux users should install the jar.

b. On your client device, launch TigerVNC. On macOS and Windows, you can double-click the binary. On Linux, install java with sudo apt install default-jre, then run java -jar VncViewer-<version>.jar, replacing the <version> placeholder with the version you downloaded.

c. In the "VNC server" field, enter the IP address of your Raspberry Pi.
