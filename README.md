# mistfieldinsights
1. Utilize this code at your own risk. There are no guarantees for functionality or security included as part of this code. You must do your own due diligence if using outside of a lab/testing environment. 

2. Mist Field Insights App requires iOS version 26.5 minimum. No other versions are currently supported or developed.

3. This App was developed using Apple Xcode. It has been tested for functionality and should work reasonably well.

4. Some basic iOS code security hardening has been performed; however, there is NO certificate pinning included in the code. This code was used to push directly to my iPhone 17 Pro for testing purposes and is not available through the Apple App Store.

5. I added images of what the app looks like on the iPhone as well as the app icon image.
   
6. Mist has the concept of User and Organizational API keys. This app utilizes an Organizational API which you will need to create for your organization. This key is then placed in the setup screen on your iPhone which will then poll your Mist Organizational data. This is app is effectively a "read only" application with no concept of pushing data or overwriting data in your organization.
   
7. This App will pull Site Wireless SLE Data on the main screen as well as Wired, WAN, and Marvis. If you do not have Wired or WAN devices in your site, there will be nothing displayed. If you have no Marvis Minis failures, it will not show anything on the main screen under Marvis.
