# Delivery-Truck-Route-Finder
The BigBasket Route Optimization project aims to improve delivery efficiency by determining the  optimal route for multiple delivery locations. This is achieved using the Travelling Salesperson  Problem (TSP) algorithm, incorporating both distance-based and travel-time-based  calculations.

Objectives 
● Minimize the total delivery cost by optimizing routes. 
● Provide two modes of optimization: distance-based and time-based. 
● Utilize OpenRouteService API for real-time travel data. 
● Ensure scalability for various delivery scenarios. 

Technologies Used 
● Programming Language: Python (Flask framework) 
● Frontend : HTML,CSS,Javascript 
● APIs: OpenRouteService API 
● Algorithms: 
○ Haversine Distance Calculation 
○ Dynamic Programming for TSP 

Implementation Details 
1. Input Processing: 
○ Receives delivery points as latitude-longitude pairs. 
○ Validates and converts inputs to float values. 
2. Cost Matrix Creation: 
○ Distance-based approach: Uses Haversine formula to compute great-circle 
distance. 
○ Time-based approach: Fetches real-time travel duration using 
OpenRouteService API.
4. TSP Solver: 
○ Implements Dynamic Programming to compute the shortest route. 
○ Reconstructs the optimal path after computing the minimal cost.
5. Flask Web Application: 
○ Provides an interface for users to input locations. 
○ Displays optimized routes and costs.


Summary 
The project successfully provides an optimized route for delivery locations, minimizing cost 
based on user preference (distance or time). The integration of OpenRouteService API 
enhances real-time accuracy, making it suitable for practical applications. 

References :  
● OpenRouteService API Documentation 
● Travelling Salesperson Problem Optimization Techniques 
● Haversine Formula for Distance Calculation
