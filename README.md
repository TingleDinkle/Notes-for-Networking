# Notes-for-Networking
My notes while I'm learning about networks!



Networking today
---------------
- Our usage of phones and internet in general consumes a large time of our day, from the moment of waking up to the moment of going to sleep.
- Convenience, companies could switch from offline working to online working for more efficiency and reach.
- Practically, a world without boundaries, you could reach just about anywhere on Earth.
- Human networking. (expand on this later)

What is a computer network?
---------------------------
- There must be a connection between two or more computing devices with the purpose of transmitting data and sharing information.
- There are two ways to connect: physical wiring or wireless.
- Computing device ex: + computer, phone, server, tablet, tv...etc
|
v
as long as it has data, it can be a computing device and can share and transmit data.

- transmitting data ex: text, file, image, voice, video,..etc

computer network ex: downloading songs to phone using a wire (qualifies as a computer network)

Network components
------------------
Three main components:
1. End devices: Data originates here, then comes through no.2 before finally reaching another end device (end device = computing device)
2. Intermediary Devices: Used to connects end devices.
3. Network media: Transfer data into "waves", more specifically, electrical pulses for metal wires within cables, pulses of light with fiber-optic cables and electromagnetic waves with wireless transmission.

Intermediary devices example: Wireless router, LAN Switch, Router, Multilayer Switch, Firewall Appliance.

Router(or access point) usage: Makes sure the "path" is efficient and makes it's way to the intended end device. (VERY loose definition, needs further clarification).

LAN switch: is ONLY used for connecting, basically nothing else

Multilayer switch: connects using many more switches, aka more pathways aka a switch with many pathways pretty much it.

About VoIP phone: It doesn't take any "data" as a normal IP Phone, but only the sound through network?? (not sure)

Network Representation
----------------------
- Physical topology: the physical location of intermediary devices and cable installation.
  
- Logical topology: illustrates devices, ports, and the addressing scheme of the network.

  
   ![image alt](https://github.com/TingleDinkle/Notes-for-Networking/blob/92a0610e98db5c7f13399e62b22eed4baee91533/image.png)

LANs and WANs
-------------
To do research on:
- Size of area covered
- Number of users connected
  
To NOT do(yet) cuz too hard:
- Number and types of services available
- Area of responsibility

Size(ascending order): PAN->WLAN->LAN->CAN->MAN->WAN

Number of users connected: 1-10->10-100->100-1000->1000-10.000->10.000-100.000->1.000.000-1.000.000.000

very small->small->small-average->average->big->very big

Abbreviation solve for dummies(me): Personal Area Network->Wireless LAN->Local Area Network->Campus Area Network->Metropolitan Area Network->Wide Area Network

Security Threats
----------------
https://docs.google.com/document/d/1Dto63rntqmhdeRu6oYHPh5Jj4sOezSn3L6Pycmb11uE/edit?usp=sharing

The report of Security Threats

Module Objectives
-----------------
Hub: Is the same as a switch, but now less commonly used because of less secure connection.

Switch: Explained in previous notes above, used the most currently along with route.

Route: Same thing as Switch notes.

Networking Devices
------------------
A Network service needs an address(or also known as IP), so they know where to send their data to.

Usually you will be using IPv4.

Networking services example: Vinaphone, Viettel,..etc

Network Interface Card
----------------------
- Is basically a physical hardware that is responsible for handling networks in your device, you almost always HAVE to have it to connect to the internet or wifi.

Hub
---
- Transfer data through multiple ports.

Switch
------
- Have a table that holds all of the information of MACs in different device and saves it to the table once a connection is made.
- Also works through ports but through a table system, which is different from a Hub.

Unrelated note: any LAN networks work with MAC addresses.

Router
------
- Finds the most efficient path to send to the end device that might receive the data through IP addresses. 

For example: your way to school have two ways, one is 5km, one is 10km, yet, the most efficient way is faster in the way that the 10km road is cleaner and there are less vehicles occupying it. Efficiency is the fastest time.

- Connects to IP Addresses outside of the LAN.

 -Gateway-Router-IP

 -Port-Switch

Cisco Packet Tracer:
>: limited

> #: full function

> (config)#: configuration


![image alt](https://github.com/TingleDinkle/Notes-for-Networking/blob/f8401d796d34f8e5cfdab52c0b6952011306c494/image1.png)

Config Settings Report for Cisco Packet Tracer(configuring passwords on routers and switches, configuring SSH on router): https://docs.google.com/document/d/1EqirhWrfimHeYUvpIfVKuo4nJQpftnXeSzVoAxbVuoA/edit?usp=sharing
