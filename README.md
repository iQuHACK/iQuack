
_Organizer's note:_ this project participated in iQuHACK 2020.

The project presentation can be found [here](https://github.com/iQuHACK/iQuack/blob/master/2020%20MIT%20QC%20Hackathon%20.pdf).

---

# Solving the Travelling Salesman Problem with Quantum Optimization and the Google Maps API #
Finding optimal routes has been a crucial and important task necessary for various applications used everyday activities, including transporting shipments across road infrastructure and plane routes which result in significant cost savings and efficiency increases for various industries. To model how the TSP can be solved, we used the Qiskit SDK along with the Google Maps API to feed route distances given 5 arbitrarily chosen points in New England. We created a distance matrix from the route distances from each point to every other point, and using these as weights between the locations, Qiskit is able to model the problem as an energy function. The problem is simulated classically, and the result is mapped onto a graph. 

