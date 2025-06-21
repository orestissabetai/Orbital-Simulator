# Orbital-Simulator
Simulation of planetary orbits in Python
# We get a more curved line for the total energy than we'd like - it's expected, with energy consrvation, for it to be horizontal. But Euler's method tends to over and underestimate the total energy, as we've broken down the orbit into lots of small straight lines in our integration method - treating the acceleration as constant in an outdated direction. 
