# Java_backend_cars_website
A REST API used as a backend system for a cars website with an in-memory H2 database, using microservices to get specific prices and car's location.

More in-depth, this backend system is composed of vehicles list services, pricing services, and location services: Vehicles API - a REST API to maintain vehicles data (CRUD), Pricing Service - a REST API to retrieve the price of a vehicle, and Location API - a HTTP client to retrieve the location of the vehicle.

In this regard, the code statements perform CRUD operations to store and retrieve vehicle data and implement an HTTP client to retrieve the address of the vehicle just by providing the latitude and longitude (it is a 'simulation' of what would be as though we were interacting with an interface such as Google Maps). It also integrates the clients (Vehicle API) with pricing services to retrieve the vehicle's price (which is a simulation as well from random prices, although it could be easily implemented through a defined price list for each vehicle and features).
