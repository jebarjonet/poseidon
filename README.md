# Poseidon
With Poseidon I manage places I like in Paris. Looks like another of my projects, [eOli](https://github.com/jebarjonet/eOli), but it is cleaner, more powerful for managing places and it is using **MeteorJS**. However compared to *eOli* there is no searching or filtering, only a raw bunch of places on a map.

## Technologies
- [Meteor 1.3.2.4](https://meteor.com/)
- Google Geocoding API
- Login with Google account
- [Leaflet](http://leafletjs.com)
- [MapBox](https://www.mapbox.com/)


### Not shown here :
- Complete administration managing places, categories and public suggestions
- Google login

### Map with places (front office)
260 places on this screen

![](https://cloud.githubusercontent.com/assets/4401230/15120406/df900874-1615-11e6-9447-29af3723bdc7.gif)

### Administration of a place (back office)
- **Autocomplete address and coordinates** from place name: Uses [Google Places by Text API](https://developers.google.com/places/web-service/search)
- **Autocomplete coordinates** from place address: Uses [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/intro)

![](https://cloud.githubusercontent.com/assets/4401230/15120408/dfa1fef8-1615-11e6-8ab8-8769cb865d2a.png)
