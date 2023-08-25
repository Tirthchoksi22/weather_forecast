# Weather Forecast App

A simple weather forecast application that allows users to retrieve a 5-day weather forecast for a specific city. The app provides temperature and humidity information for each forecasted period.

## Features

- Fetch weather forecast data from the OpenWeatherMap API.
- Display the weather forecast for the next 5 days.
- Convert UTC timestamps to IST (Indian Standard Time).
- User-friendly GUI using Tkinter and themed styling.
- Error handling for API requests.

## Requirements

- Python 3.x
- `requests` library (install using `pip install requests`)
- `tkinter` library (usually comes pre-installed with Python)
- `ttkthemes` library (install using `pip install ttkthemes`)
- `pytz` library (install using `pip install pytz`)

## Installation

1. Clone the repository or download the code.
2. Install the required libraries by running the following command:
3. Run the application:

## Usage

1. Run the application using the installation instructions.
2. Enter the name of the city for which you want to fetch the weather forecast.
3. Click the "Fetch Weather" button to display the weather forecast information for the next 5 days.
4. The app will display the time, temperature, and humidity for each forecasted period in IST.
5. In case of any errors, an error message will be shown in a pop-up dialog.

## Screenshots

![Screenshot](weather.png)

## Credits

- Weather data is fetched using the OpenWeatherMap API.
- GUI styling is done using the `ttkthemes` library.
- Time zone conversion is handled using the `pytz` library.

## License

This project is licensed under the [MIT License](LICENSE).

