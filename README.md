1. Run the batch file in Administrator Mode in windows laptop, To share your internet, enable Internet Connection Sharing (ICS): Right-click your main internet adapter (e.g., Ethernet or Wi-Fi), select Properties, go to the Sharing tab, check Allow other network users to connect through this computer's Internet connection, and select the hosted network adapter (e.g., "Local Area Connection* X") from the dropdown. \n
2. The script can create hotspot connection without requiring internet. Hotspot Name (SSID) and Password (Key) in given in the batch file (if you view it through any text viewer/editor) \n
3. A new Network Adapter is created named "Local Area Connection X" by Microsoft Hosted Network, here x is a number. Memorized the name of the network. Now go main internet adapder (such as ethernet or wifi), right click, >> Properties>>Share Tab>> Allow other network user to connect >>select the memorized Local Area Connection X network name here.
4. Once you have shared your internet and connected your devices to the hotspot, press any key to close cmd windows and the hosted network.