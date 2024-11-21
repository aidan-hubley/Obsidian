#MobileAppDesign
# Why Mobile First?
1. Websites and applications should be designed and built for mobile first
	1. Prepare for growth and emerging opportunities in mobile
	2. Forces focus and prioritization on product design based on constraints inherent in mobile design
	3. Fosters innovation by building on new, mobile native capabilities
2. "There's enough benefit to a mobile first design approach that it'sworth thinking about even if you don't have immediate plans to ship a mobile app."
## Mindset
1. Mobile is a huge mindset shift in app design
	1. Screen real estate
	2. Native location information
	3. Bandwidth constraints 
	4. Practical data entry limitations
	5. Anywhere nature of app
2. Mobile First presents a business case fr mobile first development along with designs patterns and best practices
## Constraints
1. Screen Size => keyboard size
2. Performance
3. Time & Place
4. Data volumes (not in book)
### Screen Size
1. Desktop screen = 1920 * 1080 pixels (21.68%)
2. Smartphone screen = 360 * 640 pixels (10.18%)
3. Keyboard limitations
4. Think more carefully on what you WANT the user's experience to be
### Performance
1. Several factors influence mobile app performance:
	1. Mobile device end user performance drivers
		1. Mobile device components
		2. Bandwidth capacity of wireless connection (GSM, 3G, 4G)
		3. Number of concurrent mobile users accessing the connection
		4. Nature of user accesses (streaming video vs. text messaging)
	2. Mobile app performance drivers
		1. Mobile app server performance
		2. Mobile app transaction data volume
		3. Number of concurrent mobile app users
		4. Mobile app design
	3. Thus, designing for effective mobile app performance can be tough
2. Simply states, transmitting less data will improve mobile app performance
	1. Reduce number and size of files you are sending/receiving to device
		1. Use an image sprite that allows a collection of images put into a single image
			1. A web page with many images can take a long time to load and generates multiple server requests
			2. Image sprites reduces # server requests and saves bandwidth
	## Time & Location
	1. Desktop users tend to be fixed to a location
	2. Mobile users have a much wider context of use (geography, moving)
	3. Time of day: below mobile usage patterns by time of day
	4. The closest device often determines which device is used
	## Data Volumes
	1. Data plans often place a premium on data transmission
	2. True unlimited data plans may be a thing of the past
	3. So, in addition to performance constraints, cost constraints also influence data transmission over mobile devices
# Capabilities
## The List
1. Location awareness
2. Device orientation
3. Touch
4. Camera/video integration
5. Other capabilities
	1. Device connectivity: Bluetooth
	2. Proximity: device closeness to physical objects
	3. NFC: near field communications through RFID
## Orientation
2. Skyview
3. "Accelerometers are designed to detect changes in force resulting from fall, tilt, motion, positioning, shock and vibration."
## Touch
1. Direct hand manipulation of interface
2. Touch and gestures allow us to easily navigate apps
	1. "Pull down" => refresh
	2. "Swipe" => more options
## Camera/Video Integration
1. 