# Orbital-mechanics
### Installation
The whole project has been programmed in MATLAB file using the basic Toolbox. 

## Planetary Mission 
The mission to be designed had to study the evolution of a chosen orbit taking into account J2 effect (oblateness of the Earth) and Moon perturbations. All the results have been compared with an existing satellite which shares the relevant orbital elements for those perturbation given. In addition it has also been conducted an other comparison with the GMAT (NASA) orbital evolution which shows a satisfying total match.
### Integration
The integrator is a multi-step integrator which implement step-size control and order control (ode113).

## Interplanetary Mission
The mission to be designed had to start from Jupiter, perform a flyby around Mars and in the end arrive at Venus. The aim of the following trajectory was to find a date within 40 years (from 2029/05/01 to 2069/05/01) which minimizes the total fuel consumption and the time of the journey. The program has been optimized so much that runs in few minutes thanks to the exclusion of impossible solutions.
### Integration
The integrator is a multi-step integrator which implement step-size control and order control (ode113).

