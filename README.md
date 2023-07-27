# Predicting-Aqueous-Sorption-of-Organic-Pollutants-on-Microplastics-with-Machine-Learning
This Github includes codes and data for the project of 'Predicting Aqueous Sorption of Organic Pollutants on Microplastics with Machine Learning'.

# Authors
Ye Qiu a,1, Zhejun Li a,1, Tong Zhang b, Ping Zhang a*

a Department of Civil and Environmental Engineering, Faculty of Science and Technology
University of Macau, Taipa, Macau SAR
b College of Environmental Science and Engineering, Tianjin Key Laboratory of Environmental Remediation and Pollution Control, Nankai University, 38 Tongyan Rd., Tianjin 300350, China

# Abstract 
Microplastics (MPs) are ubiquitously distributed in freshwater systems and they can determine the environmental fate of organic pollutants (OPs) via sorption interaction. However, the diverse physicochemical properties of MPs and the wide range of OP species make a deeper understanding of sorption mechanisms challenging. Traditional isotherm-based sorption models are limited in their universality since they normally only consider the nature and characteristics of either sorbents or sorbates individually. Therefore, only specific equilibrium concentrations or specific sorption isotherms can be used to predict sorption. To systematically evaluate and predict OP sorption under the influence of both MPs and OPs properties, we collected 475 sorption data from peer-reviewed publications and developed a poly-parameter-linear-free-energy-relationship-embedded machine learning method to analyze the collected sorption datasets. Models of different algorithms were compared.

# Description
data_6.csv - raw data of sorbate parameters (SSA , C%, H/C, O/H), sorbent parameters (E, S, A, B, V) and sorption coefficient. 
          Kd (L kg-1): the sorption coefficient of an organic compound under a given concentration and is the ratio of the amount of chemicals adsorbed on MPs (Qe in μg                            kg−1) to equilibrium concentration (Ce in μg L−1).
          E (excess molar refraction): stands for the London dispersive forces.
          S (dipolarity/polarizability): corresponds to the nonspecific interactions like dipole-dipole interactions
          A (H-bond acidity): represent electron-accepting capacities.
          B (H-bond basicity): represent electron-donating capacities.
          V (McGowan molar volume, cm3 mol-1 / 100) denotes the size of the molecular.
          SSA (m2 g-1), carbon content (C%), hydrogen to carbon ratio (H/C) and surface oxygen to carbon ratio (O/H) are the indicators for physical property, homogeneity,            aromaticity, and polarity of MPs.
