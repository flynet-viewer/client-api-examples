# javascript-example-googlemaps-vs

This is an example project to show how google maps integration for automatic postcode lookups linking to google maps can be implemented via the Flynet Viewer interface.

## Usage Instructions

To run this project, simply open the Visual Studio project file javascript-example-googlemaps-vs.sln (may require running Visual Studio as Administrator) and run the project locally. 

## Google Maps API Key Setup

Optionally, if you have access to a Google Maps API Key, you may use it with this project to enable a modal window view of the map, instead of opening the map in a new tab. To do this, open index.html in Visual Studio or any text editor, find line 53 with the following code:

```
var APIKey = '';
```

and insert your API Key. Please ensure that your API Key is not restricted and can access the Google Maps Embed API, Google Maps Javascript API, and Google Geocoding API.
