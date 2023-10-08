# Vayu - Airline backend system
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=&pause=1000&center=true&width=435&lines=VAYU+-+Add%2C+Search+and+Book+Flights" alt="Typing SVG" /></a>

Vayu - an airline backend system built using NODEJS. This provides fully functional robust system to search, book and add flights.

## Microservices
This system is built using microservice arcitecture which consists of three major microservices
- [Flight And Search Service](https://github.com/futoid/flightAndSearch) : This microservice provides functionality to add cities, flights, and search for flights between city A to city B.
- [Authentication System](https://github.com/futoid/authService) : Uses JWT token to authenticate the user to access the system and book fligths
- [Booking System](https://github.com/futoid/bookingService) : This microservice interacts to book flight tickets and provide availability of seats.
