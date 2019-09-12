# global_cues

The script was written for "Thermal cues drives plasticity in desiccation resistance in montane salamanders with implications for climate change" published in Nature Communications. The scripts only purpose is to create statistical maps illustrating the association between temperature and vapor pressure deficit (Figure 2). Please see the methods for more details.

The following script has three steps. The first step converts the original maps into a series of annual databases and then compiles each year into a giant database for all years. The second step then calculates the correlations between the two climatic variables, and the third step makes the maps. Be sure to change 'your_path' to the necessary directories. These were steps were broken into pieces because the code uses parrelization at various stages to greatly improve the speed.
