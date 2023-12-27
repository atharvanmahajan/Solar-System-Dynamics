# Solar System Dynamics

## Introduction  
This repository contains code for some simple astrophysical systems using numerical integration and approximation algorithms.    

Each model has various parameters which the user should tweak according to the requirement:  

All the models (except Kirkwood gaps) are implemented in [Python 3.7](https://www.python.org/downloads/release/python-377/). All constants and planetary information is fetched from Google. Visualization of the models is implemented using [matplotlib]([https://matplotlib.org]) library.  

This implementation was done as project work on the [Krittika Summer Progamme](https://krittikaiitb.github.io) as a summer project.

## Project structure  
In this repository you will find:  

- Elliptical Orbit.ipynb - Code for simulating an elliptical orbit around a massive heavenly body.   
- Hyperbolic Orbit.ipynb - Code for simulating a hyperbolic orbit around a massive heavenly body.
- Contour plot of a reduced 3 body system.ipynb - Code for visualising the potential field for a 3 body system.
- Tadpole Orbit Trajectory.ipynb - Code for tadpole orbits, a special orbit in 3 body system potential.
- Horseshoe Orbit Trajectory.ipnb - Code for horseshoe orbits, another special orbit in 3 body system potential.
- Trajectory of Photons around a Blackhole.ipynb - Code for visualising photon tracks near a massive black hole.
- Analemma.ipynb - Code for simulating Analemma tracks, aka the path of sun through the year in the sky.

## How to run code?
The easiest way is to simply copy the code from the repository into any jupiter notebook and tweak the model parameters. Make sure you have the latest verison of [Python 3.7](https://www.python.org/downloads/release/python-377/) to get accurate results

The project also relies heavily on [matplotlib]([https://matplotlib.org]) and [numpy](https://numpy.org) libraries, so make sure you have the latest versions of both the libraries. 

You can install matplotlib either through terminal using 
`pip install matplotlib`
or directly typing into jupiter notebook using
`conda install matplotlib`

Similarily, install numpy using `pip install numpy` or `conda install numpy`
