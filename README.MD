# Locations Near Me #

![picture alt](http://www.alexdzwonchyk.com/maps-demo/screenshot.png)

This is a demo of a simple client-side application that leverages the Google Maps JavaScript API to 
give a user the ability to search for locations of a given business within a specified radius. 

## Sample Data ##

Sample location data for the demo is a list of Chipotle restaurants with addresses, latitude and longitude information, 
and dummy phone numbers.

To set up a list of any locations you want, simply format the list as an array of objects with these properties: 

```javascript
{
    name: "Chipotle Boston Street",
    lat: 39.2818348,
    lng: -76.5837981,
    address: "2400 Boston St",
    city: "Baltimore",
    state: "MD",
    zip: "21224",
    phone: "(555) 555-5555",
  },
```

## How to Use ##

* Create a form in your HTML document to capture user data
* Edit the element IDs in createSearchableMap.js to reflect the fields in your form
* Save your desired list of locations, formatted as an Array of objects, as allLocations.js
* Get your own Google Maps API key, insert, and go! Visit https://console.cloud.google.com/ to create an account and activate the Maps and Geocoding APIs and generate credentials. They are free and basically unlimited (up to 40,000 calls per month for Geocoding). 

## Future Updates ##
* Add "settings" object to streamline future deployments
