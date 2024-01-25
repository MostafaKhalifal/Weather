# Weather Project

This simple command-line weather project allows you to check the current weather for a specified country or city. It retrieves data from the OpenWeatherMap API and presents it in a user-friendly format.
Features

    Displays weather information including temperature, feels like, and weather description.
    Provides a visual representation of the weather through icons.
    Supports various weather conditions, making it easy to understand at a glance.

# Prerequisites

Before using this weather project, ensure you have the following installed:

    Python 3
    argparse module
    pyfiglet library
    simple_chalk library
    requests library

You can install the required libraries using the following command:

bash

pip install argparse pyfiglet simple_chalk requests

# Usage

To check the weather for a specific country or city, run the following command:

bash

python weather.py <country/city>

Replace <country/city> with the desired location.
Configuration

Make sure to replace the api variable in the script with your OpenWeatherMap API key. You can obtain a free API key by signing up on the OpenWeatherMap website.

python

api = "YOUR_API_KEY"

# Weather Icons

The project uses emojis to represent different weather conditions. Here are some examples:

    ☀️ Clear sky
    🌧 Rain
    🌦 Partly cloudy with rain
    ⛈ Thunderstorm
    🌨 Snow
    🌫 Mist

# Example

bash

python weather.py London

This command will display the current weather information for London.
Note

If you encounter any issues or errors while retrieving weather information, make sure your API key is valid and that you have a stable internet connection.

Feel free to customize and enhance this project according to your preferences. Happy coding!
