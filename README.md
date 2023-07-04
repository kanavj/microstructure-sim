# microstructure-sim
This is my master's thesis where I build a Cellular Automata sim to simulate microstructure evolution


## Data Extractor

The data extractor is built for extracting data from a Flow 3D text output file and saving all the fields as 4D numpy arrays.

## Cellular Automata

This is the bulk of the model where we use the GARED technique to simulate microstructure evolution using files extracted from the data extractor from a Flow 3D meso scale simulation in 2D.
