# ZnO Monolayer, a theoretical study using density functional theory

## Description

ZnO 2D monolayer had been simulated using density functional theory (DFT). 
Several properties had been evaluated for the monolayer such as the monolayer geometry, the band structure and band gap and the density of states.
The results are important for understanding the physical properties of the monolayer and for the development of new materials.
For instance, the ZnO is widely used as a gas sensor.
It can be used as a thin film, nanotube, or a one layer that will be added on another material thin film.
The ZnO monolayer that had been studied in this article will give a good results for both of the nanotube and the layer on another material.
Where the monolayer is good approximation for a large nanotube.
Moreover, understanding the monolayer geometry and electronic structure will indicate its ability to be added on another material based on the material stable geometry and electronic structure. 


## Simulation

The calculation had been done using Quantum Espresso software. Firstly, the relax calculation for the stable structure had been done using the command (pw.x) with the input file (./simulation/ZnO.relax.in). Then, the self consistence field calculations had been done using command (pw.x) with the input file (./simulation/ZnO.scf.in). After that, the band calculation had been done using the same command (pw.x) with the input file (./simulation/ZnO.bands.in). Finally, the post process calculations had been done to find the band structure (command bands.x and input file ./simulation/ZnO_up.bands.in and ./simulation/ZnO_down.bands.in) and the projected density of state (command projwfc.x and input file ./simulation/ZnO.projwfc.in). Where the pseudopotential files used are shown in the directory (./simulation/pseudo/).

## Paper

The paper that summaries and have the details for all calculations results is shown in the (docs/) folder
