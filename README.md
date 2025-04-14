# Flight-Route-Planner
This project is a Python-based flight route planner using a directed graph. The program allows users to:  
- Find the shortest path between two airports.
- Identify hub airports with the most incoming and outgoing flights.
- Find airports unreachable from a given starting airport.
- Visualize the flight route graph.

# Features
Shortest Path Finder: Calculates the shortest route between two airports based on flight distances.
Hub Identification: Identifies airports with the highest inbound and outbound connections.
Unreachable Airports: Lists airports that cannot be reached from a specified starting point.
Graph Visualization: Displays a visual representation of the flight network.

# Requirements
Make sure you have the following installed:

Python 3.10 or newer
Required Python libraries:
pandas
networkx
matplotlib
scipy (installed with networkx)

# Setup Instructions
## 1. Clone the Repository
Download or clone this repository to your local machine.

## 2. Install Dependencies
Install the required libraries using pip in the terminal in VS Code:

pip install pandas networkx matplotlib
pip install pandas networkx matplotlib scipy

## 3. Prepare the Data
Ensure you have a CSV file named flights.csv in the same directory as the script. The CSV should include the following columns:

Origin_airport: Code of the origin airport.
Destination_airport: Code of the destination airport.
Origin City: The name of the state and city of where the origin airport is licated.
Destination City:The name of the state and city of where the destination airport is licated.
Distance: Distance between the two airports.
Flights: The number of flights.
Flight Date: The date the flight took place.

# Run the Program
Run the Python script in the VS Code terminal:

python Flight_route_planning.py

# Usage
Follow the menu options:

Find the shortest path: Enter the starting and destination airport codes to calculate the shortest path.
Identify hub airports: View the airports with the most inbound and outbound connections.
Find unreachable airports: Enter a starting airport to list unreachable airports.
View graph: Displays a visual representation of the flight graph for a subset of 20 nodes.
Exit: Closes the program.

## Graph Visualization Notes
The graph visualization feature shows the flight network using a subset of nodes (20 airports) to maintain clarity. The weights (distances) are displayed on edges.
