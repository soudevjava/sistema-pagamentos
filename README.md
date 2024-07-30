This microservice provides a playlist suggestion based on the current temperature of a given city or coordinates (latitude and longitude). The service integrates with a weather API to fetch the current temperature and suggests tracks according to predefined business rules.
Business Rules

    Above 30°C: Party tracks
    Between 15°C and 30°C: Pop music tracks
    Between 10°C and 14°C: Rock music tracks
    Below 10°C: Classical music tracks

Features

    Weather Information: Retrieves current temperature using a weather API.
    Playlist Suggestion: Suggests a playlist based on the temperature.
    Caching: Weather data is cached using MySQL to improve performance and reduce API calls.

Technologies Used

    Backend:
        Java
        Spring Boot
        RESTful API
    Database:
        MySQL (used as a cache)
    Deployment:
        Docker

Getting Started
Prerequisites

    JDK 11 or higher
    MySQL Server
    Docker (optional, for containerized deployment)
