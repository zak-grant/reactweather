# getweather

To launch app...
Point to location of app in cmd line or bash
run code "node app-promise.js -a 49525"
The 49525 part can be replaced by the zip code of whereever you want the weather for

This uses the google maps api to ger your coordinates based on your zip code,
this then feeds those coordinates to the darksky weather api to get your weather for your current zip code

If you run into a "Cannot read property 'geometry' of undefined" try running npm audit fix

*Update************************************************

Fixed "Cannot read property" error. Error seems to have been to due with Google GeoCoding API changing pricing structure, causing me to need to get a billing account. I changed the from Google Geocoding APi to MapQuest API, and it seems to have fixed the issue.
