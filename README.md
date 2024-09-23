# Building-the-map-of-New-York-and-other-desired-destinations
Developed the map of New York city and other destinations as Europe, Africa, Nigeria and Ikeja, the capital city of Lagos Nigeria (Africa’s Business City). Achieved this by establishing the coordinates (Longitude and Latitude) of the desired destinations and using the python language to code the necessary frameworks and display the maps. 
# map of New York with python code on Numpy
import folium
from IPython.display import display

map_center = [40.7128, -74.0060]
mymap = folium.Map(location=map_center, zoom_start=12)

folium.Marker(
    [40.7128, -74.0060],
    popup="New York",
    icon=folium.Icon(color="blue", icon="info-sign")
).add_to(mymap)

display(mymap)

# map of Nigeria with python code on Numpy
# first get the latitude and longitude of Nigeria 

import folium
from IPython.display import display

map_center = [9.0820, 8.6753]
mymap = folium.Map(location=map_center, zoom_start=12)

folium.Marker(
    [9.0820, 8.6753],
    popup="Nigeria",
    icon=folium.Icon(color="blue", icon="info-sign")
).add_to(mymap)

display(mymap)


# map of Africa with python code on Numpy
# first get the latitude and longitude of Africa
import folium
from IPython.display import display

map_center = [-8.7832, 34.5085]
mymap = folium.Map(location=map_center, zoom_start=12)

folium.Marker(
    [8.7832, 34.5085],
    popup="Africa",
    icon=folium.Icon(color="blue", icon="info-sign")
).add_to(mymap)

display(mymap)

# map of Europe with python code on Numpy
# first get the latitude and longitude of Europe
mport folium
from IPython.display import display

map_center = [54.5260, 15.2551]
mymap = folium.Map(location=map_center, zoom_start=12)

folium.Marker(
    [54.5260, 15.2551],
    popup="Europe",
    icon=folium.Icon(color="blue", icon="info-sign")
).add_to(mymap)

display(mymap)

# map of Ikeja, Lagos Nigeria with python code on Numpy
# first get the latitude and longitude of Ikeja, Lagos Nigeria
import folium
from IPython.display import display

map_center = [6.6018, 3.3515]
mymap = folium.Map(location=map_center, zoom_start=12)

folium.Marker(
    [6.6018, 3.3515],
    popup="Ikeja, Lagos",
    icon=folium.Icon(color="blue", icon="info-sign")
).add_to(mymap)

display(mymap)
