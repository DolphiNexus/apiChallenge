# Google Maps API
For our API challenge we had to get a working API from Goolge Maps. Google provides an easy code that you can use but you need to tweak some code, unless you live in australia. To be able to actually use this code you have to request an API key from Google Maps. Once you got it you add it to this line of code:
```
<script async defer src="https://maps.googleapis.com/maps/api/js?key=YOURAPIKEY&callback=initMap"></script>
```

# Fixing The Locaton
The default location in the Google Map code was Australia, this can be changed by finding your latitude and longitude. To do this I used a website called Latlong.com, it's a very simple process. You type your address and get your latitude and longitude. Once that's done you add it into your code as seen below:
```
var uluru = {lat: 00.000000, lng: -000.000000};
```

# Conclusion
This is the API Challenge and it was a project that I underastood well. I will continue to learn about APIs and how to use it to their true potential.

# Created By:
Jairo Mendoza
Developer for the team DolphiNexus(Dnex)
