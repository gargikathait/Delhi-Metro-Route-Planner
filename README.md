# 🚇 Delhi Metro Route Planner

This project simulates the **Delhi Metro Route System**, allowing users to plan metro journeys quickly and accurately via a web interface or C++ CLI.


##  Features

**Shortest Path Finder** – Compute the optimal metro route between any two stations using **Dijkstra's Algorithm**  
**Metro Line Guidance** – Each path segment shows the corresponding metro line  
**Distance Calculation** – Total travel distance (in kilometers)  
**Fare Estimator** – ₹10 base fare + ₹2/km  
**Network View** – Graph rendering of the full metro map  
**Responsive Web UI** – Built using HTML, CSS, JavaScript  
**Modular Codebase** – Cleanly separated logic for rendering, data, and styles  
**C++ CLI App** – Terminal-based version using optimized STL containers

---

## Algorithms Used

*Dijkstra's Algorithm*

- Computes shortest path in a weighted graph
- Efficient path selection considering multiple transitions
- Tracks and displays metro line changes



*Fare Calculation Formula*

Total Fare = Base Fare + (Per Km Charge × Total Distance)
Base Fare: ₹10
Per Km Charge: ₹2

  
**Sample Output**
Enter source station: Rajiv Chowk
Enter destination station: Hauz Khas

Shortest Path:
Rajiv Chowk (yellow line) -> Central Secretariat (yellow line) -> Hauz Khas
Total Distance: 10 km
Total Fare: ₹30



## How to Run Locally

```bash
# Clone the repo
git clone https://github.com/gargikathait/Delhi-Metro-Route-Planner.git

# Navigate to the project directory
cd Delhi-Metro-Route-Planner

# Compile the C++ program
g++ -o delhi_metro metroApp.cpp

# Run the executable
./delhi_metro





