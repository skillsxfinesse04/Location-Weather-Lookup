## App Title

Location and Weather Lookup (URL goes here)


## App Description

The location and weather lookup application lets a user lookup a location and it's weather.


## API and API Snippet

API: [OpenWeather](https://openweathermap.org/current)
```
{
    "coord": {
        "lon": -73.9496,
        "lat": 40.6501
    },
    "weather": [
        {
            "id": 500,
            "main": "Rain",
            "description": "light rain",
            "icon": "10d"
        }
    ],
    "base": "stations",
    "main": {
        "temp": 296.6,
        "feels_like": 296.83,
        "temp_min": 291.61,
        "temp_max": 300.39,
        "pressure": 1005,
        "humidity": 70
    },
    "visibility": 10000,
    "wind": {
        "speed": 1.79,
        "deg": 50,
        "gust": 1.79
    },
    "rain": {
        "1h": 0.15
    },
    "clouds": {
        "all": 75
    },
    "dt": 1624373099,
    "sys": {
        "type": 2,
        "id": 2037026,
        "country": "US",
        "sunrise": 1624353915,
        "sunset": 1624408223
    },
    "timezone": -14400,
    "id": 5110302,
    "name": "Brooklyn",
    "cod": 200
}
```

API2: [Rest Countries](https://restcountries.eu/#api-endpoints-all)
```
[
    {
        "name": "United States of America",
        "topLevelDomain": [
            ".us"
        ],
        "alpha2Code": "US",
        "alpha3Code": "USA",
        "callingCodes": [
            "1"
        ],
        "capital": "Washington, D.C.",
        "altSpellings": [
            "US",
            "USA",
            "United States of America"
        ],
        "region": "Americas",
        "subregion": "Northern America",
        "population": 323947000,
        "latlng": [
            38.0,
            -97.0
        ],
        "demonym": "American",
        "area": 9629091.0,
        "gini": 48.0,
        "timezones": [
            "UTC-12:00",
            "UTC-11:00",
            "UTC-10:00",
            "UTC-09:00",
            "UTC-08:00",
            "UTC-07:00",
            "UTC-06:00",
            "UTC-05:00",
            "UTC-04:00",
            "UTC+10:00",
            "UTC+12:00"
        ],
        "borders": [
            "CAN",
            "MEX"
        ],
        "nativeName": "United States",
        "numericCode": "840",
        "currencies": [
            {
                "code": "USD",
                "name": "United States dollar",
                "symbol": "$"
            }
        ],
        "languages": [
            {
                "iso639_1": "en",
                "iso639_2": "eng",
                "name": "English",
                "nativeName": "English"
            }
        ],
        "translations": {
            "de": "Vereinigte Staaten von Amerika",
            "es": "Estados Unidos",
            "fr": "États-Unis",
            "ja": "アメリカ合衆国",
            "it": "Stati Uniti D'America",
            "br": "Estados Unidos",
            "pt": "Estados Unidos",
            "nl": "Verenigde Staten",
            "hr": "Sjedinjene Američke Države",
            "fa": "ایالات متحده آمریکا"
        },
        "flag": "https://restcountries.eu/data/usa.svg",
        "regionalBlocs": [
            {
                "acronym": "NAFTA",
                "name": "North American Free Trade Agreement",
                "otherAcronyms": [],
                "otherNames": [
                    "Tratado de Libre Comercio de América del Norte",
                    "Accord de Libre-échange Nord-Américain"
                ]
            }
        ],
        "cioc": "USA"
    }
]
```


## Wireframes

![P1 Wireframe](https://user-images.githubusercontent.com/66581031/122944389-c9fdf500-d345-11eb-95d7-bef75edb2d7f.png)


## MVP 

- Use axios to make a request to get current weather conditions.
- Add type to search and dropdown menu functionality.
- Render dynamic temperature conditions, city name, time zone, and weather description.
- Style using Flexbox.
- Clear search results on query.
- Deploy site to a hosting service.


## PostMVP  

- Home page should show users current location.
- Pull users location from browser.
- Rest Countries (TBD).
- Random location button functionality
- Add animations.
- Look into localstorage so I can save data to user's browser.
- Add a filter by timezone/country section.


## Goals

|  Day | Deliverable | Status
|---|---| ---|
|Jun 21-22| Prompt / Wireframes / Priority Matrix / Timeframes | Incomplete
|Jun 23| Project Approval / Core Application Structure (HTML, CSS, etc.) | Incomplete
|Jun 23-4| Psuedocode / Code | Incomplete
|Jun 24| Initial Clickable Model | Incomplete
|Jun 25| MVP | Incomplete
|Jun 28| Presentations | Incomplete


## Priority Matrix

![P1 Priority Matrix](https://user-images.githubusercontent.com/66581031/122933019-3d9b0480-d33c-11eb-83d9-b1f82e854422.png)


## Timeframes

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Set up API | H | 3 hr | x hr | x hr |
| Core application structure (HTML) | H | 3 hr | x hr | x hr |
| Core application structure (Javascript) | H | 3 hr | x hr | x hr |
| Core application structure (CSS) | H | 3 hr | x hr | x hr |
| Set up search bar | H | 3 hr | x hr | x hr |
| Set up dropdown bar | H | 3 hr | x hr | x hr |
| Set up random location button | H | 3 hr | x hr | x hr |
| Initial clickable model | H | 3 hr | x hr | x hr |
| Minimum viable product | H | 3 hr | x hr | x hr |
| Make code clear and efficient | H | 3 hr | x hr | x hr |
| Debugging 1 | H | 3 hr | x hr | x hr |
| Debugging 2 | H | 3 hr | x hr | x hr |
| Style with Flexbot| H | 3 hr | x hr | x hr |
| Total | H | 36 hrs| x hrs | x hrs |
