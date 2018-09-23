# WeatherApp
A node shell-run app that implements web-scraping with axios' promise chaining functionality on two APIs (Google Maps API and forecast.io API) to provide information about the temperature, apparent temperature, and a general suggestion on the type of clothing to wear based on the weather. The default location is Pune.

# Example 1 (Using the default location)

```
PS I:\PROGRAM\Node.js\Weather-app> node app-promise.js  -a

Pune, Maharashtra, India

It's currently 73.08. It feels like 74.22.

It also seems to rain since humidity is 0.88..

Don't worry! It's not raining anytime soon

Look classy ;) It's pleasant outside
```

# Supplying your own arguments

## Example 2a (General Area (ie. country, state, etc)):

```
PS I:\PROGRAM\Node.js\Weather-app> node app-promise.js  -a "iceland" 

Loading weather info... 

Iceland 

It's currently 34.49. It feels like 27.19

It also seems to rain since humidity is 0.71..

Brace yourself for a rainy day

Wear a jacket duuuude!
```

## Example 2b (More specific location):

```
PS I:\PROGRAM\Node.js\Weather-app> node app-promise.js  -a "1301 lombard street philadelphia" 

Loading weather info... 


1301 Lombard St, Philadelphia, PA 19147, USA 

It's currently 81.94. It feels like 81.94

Don't worry! It's not raining anytime soon

It's nice outside! Wear something light and summer-y :)
```
