# dwynwen-burns

iPython Notebook using the Twitter API library for pulling tweets that contain keywords pertaining to celebrations on Januray 25th. Geolocation or biography location is collected, geocoded to get the latitude and longitude, and the data used to create a heatmap.

On January 25, Saint Dwynwen's Day (Welsh patron saint of lovers) is celebrated in Wales, whereas Burns Night is celebrated in Scotland.

Procedure:
* Connect to Twitter API, using the maximum API search calls on two lists of keywords. [santes dwynwen, dwynwen, saint dwynwen etc.] and [rabbie burns, burns night, robert burns etc.]
* Get the geolocation (longitude, latitude, or placename) of the tweet mentioning the above keywords. If failing this, get a location specified from the biography.
* Resolve any placename to longitude, latitude, and group occurance of tweets mentioning keywords to a location.
* Generate a heatmap using the data.
