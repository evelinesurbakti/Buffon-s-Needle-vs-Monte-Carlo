# Buffon's Needle vs Monte Carlo Simulation
Generate Pi values with Buffon's Needle and Monte Carlo

The generator (`Rng.py`) used in this library is a so-called 'Lehmer random number generator' which returns a pseudo-random number uniformly distributed between 0.0 and 1.0.  

The period is (m - 1) where m = 2,147,483,647 and the smallest and largest possible values are (1 / m) and 1 - (1 / m) respectively.  

For more details see: __"Random Number Generators: Good Ones Are Hard To Find" by Steve Park and Keith Miller.__

