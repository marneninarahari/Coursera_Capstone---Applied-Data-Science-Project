## Applied Data Science Project: Best Boroughs to Open an Indian Restaurant in San Francisco Bay Area

### Project Overview:

#### •	Business Problem: A restaurant business company would like to open an Indian restaurant in the San Francisco Bay Area, California. Since there are a large number of boroughs in the Bay Area, it is important to understand which place would be the best to start a new branch of an Indian restaurant.

#### •	Success Criteria: The success criteria of the project would be a good recommendation of borough in the Bay area for an Indian restaurant business.

#### •	Data: The San Francisco Bay Area ZIP codes and borough are downloaded from DataSF open data website. The geographical coordinates are retrieved for each borough using the geocoder and then leveraged the Foursquare AIP service to collect the location data, explored each borough of the Bay area and obtained information about different venue categories, especially restaurants, cafes, bars, pubs, etc. within 1000 m radius from the geographical coordinates.

#### •	Analytic Approach: The problem was tackled in two steps. In the first step, the objective was to a find borough where there are a lot of eateries in the Bay area. Then these boroughs are used as “Center of Attraction” for dining with different food varieties. At the same time from these boroughs, excluded boroughs where there are Indian restaurants to avoid competition among the Indian restaurants. In the second step, the goal was to select clusters similar to boroughs with Indian restaurants. K-means clustering algorithm was used to achieve these goals.

#### •	Outcomes: (i) DALY CITY, MENLO PARK and PLEASANT HILL boroughs are similar to boroughs where existing Indian restaurants are located. These are the best boroughs for a new Indian restaurant business in the San Francisco Bay Area.
