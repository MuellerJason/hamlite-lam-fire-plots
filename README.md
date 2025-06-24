# hamlite-lam-fire-plots

## Figure A: Map 
* Plots a the burden of dust and carbonaseous aerosol for a simulation with and without fire-released heat on a map.
* Can deal with data on a native ICON grid -> No preparation of the data is requiered.
* Because cartopy can't transform empty contours, the value of a single pixel on the edge of the plot is drastically increased to ensure that the highest contour is never empty

## Figure B: Crosssection
* Plots a Crosssection of dust and carbonaseous aerosol next to a domain-mean profile
* Requers data on a lon-lat grid - interpolation from native grid to lon-lat grid is necessary
