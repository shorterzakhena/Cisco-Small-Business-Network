# Cisco-Small-Business-Network
For this project, I created and configured a small network using Cisco Packet Tracer. The network consists of one Cisco router, one Cisco switch, and four PCs. 
The purpose of this project was to practice connecting network devices, configuring IP addresses, and testing communication between computers on the network.

**Network Devices**
- 1 Router - Used to provide routing and serve as the network gateway.
- 1 Switch - Used to connect the four PCs to the network.
- 4 PCs - Used to test network connectivity and communication.

**Network Topology**
The screenshot below shows the completed network topology in Cisco Packet Tracer. The four PCs are connected to the switch, and the switch is connected to the router.
Network Topology (screenshot)

**IP Address Configuration**
I configured IP addresses on the four PCs so they could communicate with each other through the network.
I also configured the router's interface with an IP address to serve as the default gateway for the PCs.

**Connectivity Testing**
After configuring the devices, I used the ping command to test connectivity between the PCs and verify that the network was working correctly.
Ping Test (screenshots)

**Troubleshooting**
During the setup, I checked the physical connections, device interfaces. IP addresses, and default gateway settings to make sure the devices were configured correctly.
If a device could not communicate with another device, I checked the cable connections and network configuration and corrected the settings before testing the connections again.

**Step-by-Step Instructions**

**1. Open Cisco Packet Tracer**
- Open Cisco Packet Tracer.
- Create a new project.

**2. Add the Network Devices**
Add the following devices to the workspace:
- 1 Cisco Router
- 1 Cisco Switch
- 4 PCs

**3. Connect the Devices**
Using the appropriate Ethernet cables:
- Connect PC1 to the switch.
- Connect PC2 to the switch.
- Connect PC3 to the switch.
- Connect PC4 to the switch.
- Connect the switch to the router.

Your basic topology should look like:
PC1 → Switch ← PC2
PC3 → Switch ← PC4
Switch → Router

**4. Configure the Router**
- Select the router.
- Open the CLI.
- Enter the appropriate configuration commands.
- Configure the router's connected interface with an IP address.
- Enable the interface.
- Save the configuration.
The router's IP address will be used as the default gateway for the PCs.

**5. Configure PC1**
- Select PC1.
- Go to Desktop → IP Configuration.
- Enter the assigned IP address.
- Enter the appropriate subnet mask.
- Enter the router's IP address as the Default Gateway.

**6. Configure PC2**
- Select PC2.
- Go to Desktop → IP Configuration.
- Enter its assigned IP address.
- Enter the appropriate subnet mask.
- Enter the router's IP address as the Default Gateway.

**7. Configure PC3**
- Select PC3.
- Go to Desktop → IP Configuration.
- Enter its assigned IP address.
- Enter the appropriate subnet mask.
- Enter the router's IP address as the Default Gateway

**8. Configure PC4**
- Select PC4.
- Go to Desktop → IP Configuration.
- Enter its assigned IP address.
- Enter the appropriate subnet mask.
- Enter the router's IP address as the Default Gateway.

**9. Verify the Network Configuration**
- Check each PC to make sure:
- The IP address is correct.
- The subnet mask is correct.
- The default gateway is correct.
Also check the router to make sure its connected interface is up/up.

**10. Test Connectivity**
Use the Command Prompt on each PC.

For example, from PC1, ping another PC:
ping [PC2 IP address]

You can also test communication with the router:
ping [Router IP address]

**11. Troubleshoot Any Problems**
If a ping fails:
- Check the Ethernet cable connections.
- Check the device interfaces.
- Verify the IP addresses.
- Verify the subnet masks.
- Verify the default gateway.
- Make sure the router interface is enabled.
- Run the ping test again after correcting the configuration.

**Skills Demonstrated**
- Cisco Packet Tracer
- Basic network topology design
- Router configuration
- Switch configuration
- IP Addressing
- Default gateway configuration
- Network connectivity testing
- basic network troubleshooting

Created By: Zakhena K. Shorter | Cisco-Small-Business-Network
