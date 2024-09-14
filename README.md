1) The folder contains the colab files in Python that were used to generate the data, tests and
   illustrations used in the LaTeX paper:

   The colab files APOALB_00a* and APOALB_00b* generate the figures for the reservoir computers
   The APOALB_00c* colab file generates the outline of the Lorenz system as rho changes
   APOALB_01* colab file displays the Lorenz system attractor for a certain rho
   APOALB_02* colab file trains an RC on the Lorenz system for a certain rho

   APOALB_03* colab files generate datasets on the Lorenz system as rho changes
     a) rho in [0.330], b) rho in [166.167].
   APOALB_04* colab files generate the Lyapunov exponents of the "true" Lorenz system as rho changes
     a) rho in [0,330], b) rho in [166,167].

   The APOALB_05* colab file optimises the hyperparameters of n RC with the previously generated datasets
     a) rho in [0,330], b) rho in [166,167].
   APOALB_06* colab files calculate Laypunov exponents for the various tests (N=200,N=400 and intermittence with N=200,400)
   
   colab file APOLB_09* generates the plots of the z variable (intermittence) used in the paper
   APOALB_10* colab files generate the figures used in the paper
   
   The zipped files dataset_part_1*.zip and dataset_part_2*.zip contain the datasets generated
   to perform the tests (they were compressed because they took up too much space)
   
   The *.png files are the figures saved during the colab execution

2) the zipped file climate.zip contains:
   a) the Lyapunov exponents of the "true" Lorenz system as rho changes
   b) for each seed, the hyperaparameters and Lyapunov exponents calculated using the RCs (as rho changes)

