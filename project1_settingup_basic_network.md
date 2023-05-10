## Bitacora

### 10/05

1. Asked gpt4 for the first project: 

"Exercise 1: Basic Basic - Setting Up a Basic Network

Objective: To connect two PCs through a switch.

Project Description: The students will learn how to set up a basic network where two computers are connected to each other through a switch. They will also learn about the initial configurations of these devices.

Tasks:

1.Configure two PCs with IP addresses from the same subnet.
2.Connect the two PCs to a switch using straight-through Ethernet cables.
3.Test the connectivity using the ping command.

2. We already did the connection. Next step, understanding it.


- By connecting a switch to a pc, the used cable is straight copper cable.

- Crossover cable: is a type of Ethernet cable, used for: pc-pc, switch-switch, router-router, hub-hub.
-Straight Through cable: cable used for LANs. Used for connecting: pc-switch, pc-hub.

- Understand how to acceed to switch by console, telnet, vty.

.3 Understanding the connection to a switch for stting it up. Gpt4 answer.

Checking the settings of a switch in Cisco Packet Tracer involves interacting with the Command Line Interface (CLI) of the switch. Here's a step-by-step guide on how to do this:

**Step 1:** Open your project in Cisco Packet Tracer.

**Step 2:** Click on the switch that you want to check the settings for. This will open a new window with several tabs.

**Step 3:** Go to the CLI (Command Line Interface) tab.

**Step 4:** If the switch is not already turned on, turn it on. Wait until the command line appears. It should end with a ">" symbol.

**Step 5:** To view the switch's settings, type "enable" at the command prompt, and press "Enter". This will take you to the Privileged EXEC mode (indicated by a "#" symbol).

**Step 6:** Now, type "show running-config" and press "Enter". This will display the current configuration of the switch, including interface settings, VLAN configuration, and more.

You asked about using console or VTY (Virtual Teletype) for this purpose. These are ways to access a device's CLI:

1. **Console access:** This is typically used for direct communication with the device. In Packet Tracer, this would simulate plugging a console cable from your PC into the console port of the switch. To do this, you would select a PC and the console cable from the "Connections" options, then click on the PC and the switch to connect them. Once connected, on the PC, you would go to the "Desktop" tab, then the "Terminal" program, and you would be at the CLI of the switch.

2. **VTY access (SSH or Telnet):** This is typically used for remote communication with the device over the network. In Packet Tracer, this would simulate connecting to the switch from a PC on the network. You would need to configure the VTY lines on the switch (using the "line vty 0 4" and "login" commands, and setting a password), and also set an IP address on the switch. Then, on a PC, you would go to the "Desktop" tab, then the "Command Prompt", and use the "telnet <switch IP address>" or "ssh -l <username> <switch IP address>" command to connect to the switch.

Another way to check the settings of a switch in Packet Tracer is using the GUI:

**Step 1:** Click on the switch.

**Step 2:** Go to the "Config" tab.

**Step 3:** On the left, you will see several options such as "FastEthernet0/1", "FastEthernet0/2", etc. These represent the different ports on the switch. Clicking on them will show you the settings for that port.

**Step 4:** To check the switch's global settings, click on the "Settings" option on the left. This will show you the name of the switch, its banner, and other global settings.

**Step 5:** To check the VLAN settings, click on the "VLAN Database" option on the left. This will show you the VLANs that are currently configured on the switch.