# Identifying-best-hotel-locations
Web-scrapping popular tourist attractions, Forward geocoding the coordinates and address from the place names then interactively mapping places on map. 


Utilized web-scrapping technique using package BeautifulSoup to collect popular tourist attractions in Portsmouth, United Kingdom. Then passed the place names collected from the two websites (urls) to Nominatim the geocoding package  used to extract the coordinates and addresses of the places which were then used to map the hotel location with tourist attractions which could identify the best hotel location.

PlanetWare | Bryan Dearsley: https://www.planetware.com/tourist-attractions-/portsmouth-eng-hmp-po.htm
Expedia: https://www.expedia.co.uk/Things-To-Do-In-Portsmouth.d553248634335196573.Travel-Guide-Activities


Packages: #pandas #numpy #BeautifulSoup #requests #Nominatim #geopandas #geopy #geopy.geocoders #geopy.extra.rate_limiter

To Improve: 
1) Make functions to pass the list of shortlisted hotel names (possibly from another webscrapping) with prices and selcting best location hotels.
2) Optimising travel iternaries

P.S. I'm going to Portsmouth soon so the hotel is the one I picked (hope I have this resouce while doing my hotel research ;) )
