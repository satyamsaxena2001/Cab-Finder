# CAB FINDER

->co-ordinates of all the cabs in the city stored in a text file in JSON format.
->GPS co-ordinates(in degrees) of a person who needs a cab also given. 
->this program will find the user-id and name of all the cab drivers available in 50 km proximity.


## Logic
- Obtain latitude and longitude of each cab as a string with their
user-id and name from the JSON input file.
- Convert latitude and longitude of the cab present in string to double.
-  Convert latitude and longitude of both, the user and the cab present in
degrees to radians.
- Calculate distance between the user’s location and the cab using Great Circle
Distance formula.
- If distance is found to be less than or equal to 50 kms then output the user-
id and name of the cab driver to a new file else take no action.
