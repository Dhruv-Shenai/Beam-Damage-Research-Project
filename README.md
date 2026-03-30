Simple_analysis_for_cif_pets file looks at incomplete datasets like thge schematic one and the other samples with incomplete data. E.g. glycine with no Lorentz correction. 
WIlson_Plot_analysis produces most of the graphs and data processing for the abiraterone acetate and paracetamol sample. A cif_pets file is needed, a lroentz correction file and the kinematic simulation for the g vectors. 
mrcanalysisforgifs turns the gifs into individual frames to analyse and also has a brief blob detection algorithm which I tried to use to detect unit cell expansion. 
A_beam_damage_dhruv contains the required material to make dynamical simulations of any cif_pets/cif combination. 
