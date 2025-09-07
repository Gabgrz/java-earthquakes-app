# Java Earthquakes App

Interactive earthquake visualization application built with Java and Processing.

## Features

- **Interactive Map**: Displays recent earthquakes (magnitude 2.5+) on a world map
- **Earthquake Markers**: Different visual styles for land vs ocean earthquakes
- **City Markers**: Shows major cities with threat circle analysis
- **Click Interactions**: Click earthquakes to see affected cities, click cities to see nearby earthquakes
- **News Integration**: Press Ctrl while hovering over earthquake markers to search for recent news
- **Data Sorting**: Automatically sorts earthquakes by magnitude

## Data Sources

- **Earthquakes**: USGS real-time earthquake feed (2.5+ magnitude)
- **Cities**: Major world cities from city-data.json
- **Countries**: Geographic boundaries from countries.geo.json

## Usage

1. Run `EarthquakeCityMap.java` for the main earthquake visualization
2. Run `AirportMap.java` for airport and flight route visualization
3. Use mouse to interact with markers
4. Press Ctrl while hovering over earthquake markers for news search

## Requirements

- Java 8+
- Processing 3.x
- Unfolding Maps library
- Internet connection (for real-time data)

## Project Structure

- `src/final_version/` - Main application files
- `src/parsing/` - Data parsing utilities
- `data/` - Static data files and test feeds
- `lib/` - Required JAR libraries

## Author

Gabriel Garoz & UC San Diego Intermediate Software Development MOOC team
