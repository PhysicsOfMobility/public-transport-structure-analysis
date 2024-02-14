Readme: Public Transport Structure Analysis

The following is a code designed to analyse public transport routes globally.
The code is commented to describe the functioning of each section.
Here is an overview of what the code does:

-> The code inputs the route network for a city and the corresponding spatial structure of it's public transport network.
-> It breaks the route into segments of tunable length and compare the actual length of the route segment with the shortest length possible between the segment ends
-> The code can be used to analyze how the detours are distributed across the route and the total detour of a route.
-> Further analysis can be done to understand the connectivity between routes, which is the ease of switching between the routes.
-> The code also has provision to import population distribution data for cities and calculalte the weighted detour analysis for routes.
-> The code can also be used to calculate several density parameter to understand city structure as commented in the code.
-> Several correlations can also be found between route detours and route properties such as fraction of length in city centre, route length and population served per unit length.

Data description:

-> The population data used is from the Kontur population dataset.
-> Street network data is extracted from OpenStreetMaps and is tagged with the file name 'map'.
-> Bus route data has been extracted from OpenStreetMaps and broken bus lines have been filtered.

For any doubts further communication can be done to kush_mohan.mittal@tu-dresden.de