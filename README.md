# Identifying-best-hotel-locations
Web-scrapping popular tourist attractions, Forward geocoding the coordinates and address from the place names then interactively mapping places on map. 


Utilized web-scrapping technique using package BeautifulSoup to collect popular tourist attractions in Portsmouth, United Kingdom. Then passed the place names collected from the two websites (urls) to Nominatim the geocoding package  used to extract the coordinates and addresses of the places which were then used to map my hotel location with tourist attractions which could help me plan my iternary for the trip.

Hats tip for selecting that hotel. Close to most of the locations. Yayyy!!

PlanetWare | Bryan Dearsley: https://www.planetware.com/tourist-attractions-/portsmouth-eng-hmp-po.htm

Expedia: https://www.expedia.co.uk/Things-To-Do-In-Portsmouth.d553248634335196573.Travel-Guide-Activities


Packages: #pandas #numpy #BeautifulSoup #requests #Nominatim #geopandas #geopy #geopy.geocoders #geopy.extra.rate_limiter

Used alteryx for spatial data processing- Alteryx data file attached.

To Improve: 

a) Make functions to pass the list of shortlisted hotel names (possibly from another webscrapping) with prices and selcting best location hotels.

b) Using ML to pick hotel location and optimisng travel iternaries

How to read file:

Extracted places from PlanetWare site on Portsmouth Places to Visit-1 stored in PortsmoutPlaces.csv and the combined with Expedia data in Portsmouth Destination list and Mapping ipynb file. Portsmouth Cleaned data used in Alteryx to do data pre processing (could have been done in python). Final Data in PortsmouthPlacesFinal and Portsmouth Map.jpg generated through alteryx.

P.S. I'm going to Portsmouth soon so the hotel is the one I picked (hope I had this resouce while doing my hotel research ;) )

