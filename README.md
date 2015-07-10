# Roku-Remote
Simple, mobile-friendly Roku remote webUI using jQuery. 

Note: There is a free Roku app for both Android and iOS. This was created as a POC and will be used with another project.

! Mainline currently broken while I pretty things up. (using boilerplate, adding functionality)

Screenshot: http://imgur.com/hAJOEYA

## Setup
1. Copy 'roku.html' to a server on your home network.
2. Open roku.latest and enter your Roku's IP in the IPADDR variable 
* var IPADDR = "http://YOURIPHERE:8060";
3. Open 'roku.latest' in your browser and enjoy

## Additional Information and Notes
* More about Roku here: https://www.roku.com
* API Docs: http://sdkdocs.roku.com/display/sdkdoc/External+Control+Guide
* I am not affiliated with roku.

## Tasks
* Use API text search functionality (would be great on mobile w/ Swype).
* Move the css, html, and js/jq to a separate file
* Make pretty

## Changelog
* 21 JUN 2015 Use an IP variable instead of hard-coding the IP 50 times. 
* 21 JUN 2015 Link to common Apps
