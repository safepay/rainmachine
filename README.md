# Rainmachine Willyweather Australia Parser
A parser for the RainMachine smart watering system using the API from www.willyweather.com.au

Note that I am not a professional (or even amateur!!) programmer.
I wrote this because of the lack of local Australian support from the RainMachine system.
However, the built in global parsers do a pretty good job.

The Willyweather service is a commercial API with the first 5000 calls free, then a cost based on the type of data you want to access.
The typical cost is aroung $0.09 per 1000 calls for a single weather station, which is what the code is written to handle.

If you have any suggestions or can clean up my code then thanks in advance!

The main confusion I have is how RainMachine stores time. That is why the code has references to both local and UTC time, but I am logging with local so that my data matches that from services such as OpenWeatherMaps.
