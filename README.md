# README #

These scripts are a "quick-to-test" precursor to the EpidemicSimulator project. The most interesting source is inside the "WorkingModels" directory which contains
models that work.

Epidemic models:

* Stochastic Cellular Automata: SEIRS (Susceptible Exposed Infected Recovered), SIS, SIR, SEIS, SIRS
* Numerical ODE based: SIR with no birthds/deaths and SIR with birthds/deaths
* Cellular Automata"Forrest Fire": SIR
* Coupled Lattice 2D: with Moore and von Neumann neighborhoods

Features:

* Pygame for 2D image visualizations.
* Numpy and PyLab for Graph visualizations and random distributions.

The scripts use:

​* Python 2.7 32bit version for win32 (installed the package Python 2.7 Anaconda 2.3.0  Windows 32bit version from https://www.continuum.io/downloads ).
It includes Numpy (for numerics/random) and Pylab (for plots).
* IDE: PyCharm 4.5 Professional
* 2D graphics: PyGame version 19.2a0 Win32 for Python 2.7. (http://pygame.org/ftp/pygame-1.9.2a0.win32-py2.7.msi )