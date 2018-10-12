# wildfire

# The main theme corresponds to the detecton and prevention of wildfires.

Wildfires are the one of the most devastating natural disasters. This can be caused by a slightest of the spark generated in some way very distant in the forest, thunderstorms generated which struck some part of the wildlife. It can spread quickly to over vast areas which may extend upto a continent. Unlike most of the natural disasters, wildfires when detected in early stages can be prevented with slightest of the expenditure.

Detection:

The major issue with the project is to identify the hotspots which are very potential to have a wildfire.To obtain this hotspots we use satellite images available. The moderate resolution imaging spectroradiameter analyzes images obtained from NASA and checks for the fire from the surface temperature. We use the data available from the last 15 years and feed it to as training data to the software. This already existing data can be used to identify the potential regions of wildfire with a particular scope of area(in terms of geographical area).These hotspots may or maynot be the regions where the actual disaster may occur. 

Apart from this, we monitor the daily images obtained to identify the regions of fire( Using image processing to do so). We use these datasets to compare with the hotspots available in the database of hotspots. We use neural computing based techniques to generate a probability factor using both of the available data. We define two characterstics to determine the factor, namely support and confidence.
support is more related to past data and the database available to us.Confidence corresponds to when support then the determinism of disaster in the past data.

This way we generate the probability of an event and determine its base point using satellite loacation to act quickly.
