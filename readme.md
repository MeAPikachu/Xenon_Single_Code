This repository is the code for the single phase gain simulation, and the report itself is here at the . 

Basic Files:
- reproduce_comsol.ipynb : Run this notebook on a Windows workstation installed with Comsol, this notebook will modify its parameters and export the simulation results automatically
- reproduce.ipynb : Simulation notebook. Run it on the most powerful server.
- template_voltage.ipynb : Analysis notebook. Run it whenever you want.
- reproduce.mph : the mph(Comsol) file itself



Example Files:
- field.txt : Electric field file exported by Comsol 
- streamline.txt : Electric streamline file exported by Comsol 
- singlecell4.h5 : convert the electric field txt file into h5df 
- singlecell_stream.h5 : convert the electric streamline txt file into h4df 
- parameter.txt : The basic parameter about the comsol mph file and the simulation settings
- information{timestamp}.txt : Simulation parameters and the simulation results identified by its process ID, we mainly analyze the result from this txt file. 





