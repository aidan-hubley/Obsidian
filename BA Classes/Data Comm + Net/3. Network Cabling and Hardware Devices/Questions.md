# 3.1 Questions

1. You're installing network wiring for a new Ethernet network at your company's main office building. The project specifications call for Cat 5e UTP network cabling and RJ45 wall jacks. Near the end of the project, you run out of wire before the last few runs are complete. You have a spool of Cat 3 network cable in storage. Upon closer inspection, it appears very similar to the Cat 5e wiring. To finish the project, should you use the Cat 3 cabling as a substitute for the Cat 5e cabling?
	1. No. Cat 5e cabling has more twists per inch than Cat 3 cabling, reducing crosstalk and supporting higher data rates.
2. Which of the following cable types often includes a solid plastic core that keeps the twisted pairs separated?
	1. Cat 6
3. You're adding new wires in your building for some new offices. The building has a false ceiling that holds the lights and provides an air path for heating and air conditioning. You'd like to run your Ethernet cables in this area. Which type of cable must you use?
	1. Plenum-rated cable
4. Why might you use an RJ11 connector?
	1. You want to connect your computer to the internet with a DSL modem.
5. Which of the following connectors is used with Ethernet 100BaseTX networks?
	1. RJ45
6. Which of the following connector types would you most likely use to connect to a T1 WAN service?
	1. RJ48c
7. You're working with an older 10Base2 Ethernet network. Which of the following connector types will you MOST LIKELY encounter?
	1. BNC
8. Which of the following are characteristics of a coaxial network cable? (Select two.)
	1. It has a conductor made from copper in its center.
	2. It uses two concentric metallic conductors.
9. You have a small home network connected to the internet using an RG-6 cable. You need to move the router, but you can't find anymore RG-6 cabling. Which cable type could you use instead?
	1. RG-59
10. You've just signed up for a broadband home internet service that uses coaxial cabling. Which connector type will you MOST LIKELY use?
	1. F-type

# 3.2 Questions

1. Which of the following are advantages of using fiber optic cabling for a network? (Select two.)
	1. Immunity to electromagnetic interference
	2. Greater cable distances without a repeater
2. Which of the following connectors are used with fiber optic cables and include both cables in a single connector? (Select two.)
	1. MTRJ
	2. LC
3. Which of the following cables offers the best protection against EMI?
	1. Single-mode fiber optic
4. Which of the following are characteristics of an LC fiber optic connector? (Select two.)
	1. They use a housing and latch system similar to an RJ45 UTP connector.
	2. They are half the size of standard connectors.
5. Which of the following connectors is used with fiber optic cables and requires that you use a twisting motion to connect it?
	1. ST
6. Which of the following are characteristics of an MTRJ fiber optic connector? (Select two.)
	1. They use metal guide pins to ensure accurate alignment.
	2. They can be used with multi-mode fiber optic cables.
7. Multi-mode fiber is designed to operate at which of the following wavelengths?
	1. 850 nm and 1300 nm
8. Which of the following connectors usually require polishing as part of the assembly process? (Select two.)
	1. SC
	2. ST
9. Which of the following is true about single-mode fiber optic network cabling?
	1. Its central core is smaller than the standard multi-mode fiber optic cabling core.
10. Which type of optical fiber is normally used to connect two buildings that are several kilometers apart?
	1. Single-mode fiber


# 3.3 Questions
1. You need to terminate a Cat6 UTP cable with an RJ45 connector. Your organization's IT policy states that all cable connectors must be wired according to TIA568B standards. Drag the UTP wire on the left to the correct pin on the RJ45 connector on the right.
	1. Pin 1 - White w/ Orange Stripes
	2. Pin 2 - Solid Orange
	3. Pin 3 - White w/ Green Stripes
	4. Pin 4 - Solid Blue
	5. Pin 5 - White w/ Blue Stripes
	6. Pin 6 - Solid Green
	7. Pin 7 - White w/ Brown Stripes
	8. Pin 8 - Solid Brown
2. Which of the following describes the point where the service provider's responsibility to install and maintain wiring and equipment ends and the customer's begins?
	1. Demarc
3. You have a network that occupies all three floors of a building. The WAN service provider has installed the line in a wiring closet on the main floor. You have a wiring closet on the two remaining floors directly above the wiring closet on the main floor. What would you use to connect the wiring closets together?
	1. Vertical cross connect
4. Which recommendation should you follow while using 110 blocks for connecting Cat5 and higher data cables?
	1. Keep wire pairs twisted up to within one half of an inch of the connector.
5. Which of the following uses metal clips placed over plastic slots to connect individual copper wires?
	1. 110 block
6. You are preparing to attach wires in a 110 block. You want to connect the wires and trim off the excess at the same time. Which of the following should you do? (Select two.)
	1. Point the cut side of the tool towards the wire end.
	2. Use a punch down tool with a notched blade.
7. Which of the following terms identifies the wiring closet in the basement or ground floor that typically includes the demarcation point?
	1. MDF
8. Which of the following terminates individual wires from a 25-pair or 100-pair cable using female RJ45 ports?
	1. Patch panel
9. Which tool should you use to extend network services beyond the demarc?
	1. Punch down tool
10. You are making Ethernet drop cables using Cat5e cables and RJ45 connectors. You need to remove the plastic coating over the cable to expose the individual wires. Which tool should you use?
	1. Cable stripper

# 3.4 Questions
1. You've decided to implement Gigabit Ethernet on your network; each switch port is connected to a single device. Following the installation, you find one device connected to a switch that's only running at 100 Mbps. Which of the following is MOST LIKELY the cause?
	1. Crosstalk
2. You have a cable internet connection at home. The installer had connected the router near the outside wall of your house with RG6 cable. You move the cable router a distance of 50 meters using RG8 cables and special connector adapters. Which condition are you MOST LIKELY to experience?
	1. Echo
3. While viewing the status of interfaces on a Cisco switch, you see an abnormally large number of CRC errors on one interface. This interface is connected to a user's workstation that is located in a cubicle on the second floor. What could cause this to happen?
	1. A strong EMI emitter near the cable connected to that interface.
4. You need to replace a fiber optic cable that's connecting two switches together. You inspect the existing cable and determine that it uses LC connectors. You also notice that the cable's ferrule has a slight slant to it. Which polish grade should you use to replace the existing cable?
	1. Angled Physical Contact polish
5. You're building a new network for a small financial services startup company. Security is paramount, so each organization within the company will have its own network segment separated by a router. However, funds are limited, and you've been asked to keep costs to a minimum. You've acquired a used fiber optic switch, and you want to use it to create a fiber optic backbone that interconnects all of the routers. You've purchased several used single-mode GBIC modules on eBay that you'll install on each router to allow them to connect to the switch. Both the switch and the GBIC modules use MTRJ connectors. You connect each module to the switch with 1-meter multimode patch cables. Will this implementation work?
	1. No. You shouldn't use multi-mode patch cables with single-mode GBIC modules.
6. You're building a new network for a small financial services startup company. Security is paramount, so each organization within the company will have their own network segments separated by routers. Funds are limited, and you've been asked to keep costs to a minimum. You've acquired a used fiber optic switch, and you want to use it to create a fiber optic backbone that interconnects all of the routers. You've purchased several used multi-mode GBIC modules on eBay that you'll install on each router to allow them to connect to the switch. Both the switch and the GBIC modules use MTRJ connectors. You've purchased several used 1-meter, multi-mode patch cables from Amazon. But when they arrived, you noticed that they use LC connectors. Fortunately, with some force, you found that you're able to get the LC connectors on the cables to lock into the MTRJ connectors on the GBIC modules and on the switch. Will this implementation work?
	1. No. You should purchase patch cables that use MTRJ connectors.
7. You want to measure the voltage, amps, and ohms of various devices. Which tool should you use?
	1. Multimeter
8. You're working with an existing fiber optic installation in your building. You want to know the length of each cable that runs through the walls. Which tool should you use?
	1. OTDR
9. Users report that the internet is no longer accessible. You suspect that the line connecting your building to the internet isn't working properly. Which of the following allows the service provider to remotely test the local loop?
	1. Smartjack
10. You've connected a cable certifier to an RJ45 wall jack, and the output shown below is displayed on the device. What does this output indicate? (Select two.)![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_trouble_tools_np6/2021-06-23_12-02-37.png)
	1. This is a crossover cable.
	2. The cable is functioning correctly.


# 3.5 Questions
1. A host wants to send a message to another host that has an IP address of 115.99.80.157, but it does not know the destination device's hardware address. Which protocol can be used to discover the MAC address?
	1. ARP
2. You have a server that has a 100BaseFX network interface card you need to connect to a switch. The switch only has 100BaseTX switch ports. Which device should you use?
	1. Media Converter
3. At which OSI model layer does a media converter operate?
	1. Layer 1
4. Which of the following is a valid MAC address?
	1. AB.07.CF.62.16.BD
5. Which of the following is a valid MAC address?
	1. C0-34-FF-15-01-8E
6. Which of the following are true about a MAC address? (Select two.)
	1. It is typically represented by hexadecimal numbers.
	2. It is a 48-bit address.
7. Which of the following statements accurately describe how a modem works? (Select two.)
	1. It demodulates analog data from a telephone network into digital PC data.
	2. It modulates digital data from a PC into analog data and transmits it on a telephone network.
8. Which network component connects a device to transmission media and allows the device to send and receive messages?
	1. Network interface card
9. You want a switch to have the ability to modify the media type the switch port supports. Which type of module might you use to make this possible?
	1. SFP
	2. GBIC
10. Which device sends signals from a computer onto a network?
	1. Transceiver


# 3.6 Questions
1. Which of the following hardware devices regenerate a signal out of all connected ports without examining the frame or packet contents? (Select two.)
	1. Repeater
	2. Hub
2. How do switches and bridges learn where devices are located on a network?
	1. When a frame enters a port, the source MAC address is copied from the frame header.
3. At which OSI layer does a router operate to forward network messages?
	1. Network
4. At which layer of the OSI model do hubs operate?
	1. Physical
5. Which of the following BEST describes how a switch functions?
	1. It connects multiple cable segments (or devices) and forwards frames to the appropriate segment.
6. You are the network administrator for a small organization. Recently, you contracted with an ISP to connect your organization's network to the internet. Since doing so, it has come to your attention that an intruder has invaded your network from the internet on three separate occasions. Which type of network hardware should you implement to prevent this from happening again?
	1. Firewall
7. Which of the following hardware devices links multiple networks and directs traffic between networks?
	1. Router
8. Which of the following creates a visual representation of physical components along with a clearly defined set of principles and procedures?
	1. Floor plan
9. Rack heights vary from a few rack units to many rack units. The most common rack heights are 24U and 42U. How tall is a 24U rack?
	1. 42 inches
10. A rack's height is measured in rack units (Us). How tall is a single rack unit?
	1. 1.75 inches tall