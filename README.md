# **Capacited Vehicle Routing**
This is a real-time implementation of the Capacited Vehicle Routing Problem
## Minimization of Transportation Cost of Raw Milk for Dairy Plant
Dairy industry collects raw milk from milk producers by transporting it in a various tankers/other vehicles of various capacities. Transportation charges paid by dairy industry are based on kilometre/per litre. Transportation cost is directly related to type of vehicles, vehicle capacity, and vehicle route for milk collection. The exact problem faced by the dairy was:
  1. Selection of Transportation Vehicle
  2. Selection of Vehicle Capacity
  3. Milk Collection Route Design  
![Overview](https://github.com/jainamshah17/capacited-vehicle-routing/blob/master/Images/magic.PNG)  
### Algorithm
The input parameters for the CVRP Algorithm are: List of all available transportaion vehicles, capacities of all the vehicles, co-ordinates of all the locations (from where milk is to be collected).  
![Before](https://github.com/jainamshah17/capacited-vehicle-routing/blob/master/Images/cvrp_b4.PNG)  
It provides the most optimized routes, utilizing the vehicle capacities i.e. vehicle has to travel the least distance collecting maximum raw milk.  
![After](https://github.com/jainamshah17/capacited-vehicle-routing/blob/master/Images/cvrp_after.PNG)  
### Web-Application
Using the website, dairy personels can visualize the routes information on Google Maps, on clicking "Calculate" algorithm will be executed based on latest data available. Also all the parameters such as vehicles, capacity of vehicles and locations can be updated through website.  
![Route on Google Map](https://github.com/jainamshah17/capacited-vehicle-routing/blob/master/Images/website.png)  
### Simulation Results
We collected some real data from the dairy and ran our algorithm on that data, following is the result; Transportaion cost of raw milk reduced from Rs 0.69 per litre to Rs 0.57 per litre  
![Simulation Result](https://github.com/jainamshah17/capacited-vehicle-routing/blob/master/Images/result.png)  
### Technology Stack
Algorithm: Python, OR-Tools (Open Source Google Library)  
Web-App: PHP, MySQL, HTML, CSS3, JavaScript  
Mobile-App: Cordova  
### References
https://developers.google.com/optimization/routing/cvrp
