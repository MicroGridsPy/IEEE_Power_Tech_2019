Micro-Grids
========================

This is code used for the publication: [https://doi.org/10.1109/PTC.2019.8810571]

### Description

The Micro-Grid library main objective is to provide an open source alternative to the problem of sizing and dispatch of energy in micro-grids in isolated places. It’s written in python(pyomo) and use excel and text files as input and output data handling and visualization. This Branch was created to contain the data for the  13th IEEE PowerTech 2019 paper "Two-stage stochastic sizing of a rural micro-grid based on stochastic load generation". 

Main features:

    Optimal sizing of Lion-Ion batteries, diesel generators and PV panels in order to supply a demand with the lowest cost possible.
    Optimal dispatch from different energy sources.
    Calculation of the net present cost of the system for the project lifetime.
    Determination of the LCOE for the optimal system.


### Main developpers


Francesco Lombardi <br/>
Politecnico di Milano, Milan <br/>
E-mail: francesco.lombardi@polimi.it<br/>

Sergio Balderrana <br/>
University of Liege, Belgium - Universidad Mayor de San Simon, Bolivia <br/>
E-mail: slbalderrama@doct.ulg.ac.be <br/>
 
Nicolò Stevanato <br/>
Politecnico di Milano, Milan <br/>
E-mail: nicolo.stevanato@polimi.it <br/>

Sylvain Quoilin <br/>
University of Liege, Belgium. <br/>
E-mail: squoilin@ulg.ac.be <br/>
 
### Required libraries

The python libraries needed to run Micro-Grids are the following:

    -Pyomo Optimization object library, interface to LP solver (e.g. CPLEX)
    -Pandas for input and result data handling
    -Matplotlib for plotting


### Licence
This is a free software licensed under the “European Union Public Licence" EUPL v1.1. It 
can be redistributed and/or modified under the terms of this license.

### Getting started

To start using the Micro-Grid library please Go to Documentation/_build/html and double click in the archive index.html. This will open a Documention in html format. Please read carefully the tutorial part of this documentation in order to understand how to setup and use Micro-Grids library.

