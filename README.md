# City-Mileage

# Greedy Approach to Hamiltonian Problem

## Overview  
This program determines the best city to start from in order to make a round trip with enough gas.  
It calculates the distance between the cities, the fuel availability at each city, and the car's miles per gallon (MPG).  

## Features  
- Determines the best starting city based on gas availability, city distances, and car's MPG  
- Accepts inputs for the number of cities, distance between cities, fuel availability, and car's MPG  
- Outputs the best city to start at for a successful round trip  

## Installation  
1. Open a terminal  
2. Run the following command:  
   ```bash
   python3 city_main.py


## Example runs

$ python3 city_main.py
Enter the number of cities for the trip: 4
Enter the distance between city 0 and city 1: 100
Enter the distance between city 1 and city 2: 200
Enter the distance between city 2 and city 3: 150
Enter the distance between city 3 and city 0: 250
Enter the fuel available at city 0: 30
Enter the fuel available at city 1: 50
Enter the fuel available at city 2: 40
Enter the fuel available at city 3: 60
Enter the MPG for your car: 20
The best starting city is: City 1


$ python3 city_main.py
Enter the number of cities for the trip: 3
Enter the distance between city 0 and city 1: 150
Enter the distance between city 1 and city 2: 200
Enter the distance between city 2 and city 0: 100
Enter the fuel available at city 0: 20
Enter the fuel available at city 1: 30
Enter the fuel available at city 2: 25
Enter the MPG for your car: 15
No valid starting city found
