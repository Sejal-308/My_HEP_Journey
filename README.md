# My_HEP_Journey
This repo is for documenting the codes that I have written as part of my journey of doing data analysis, reconstruction, simulations, regression etc. in High Energy Physics. Here's what I've done till now:
1. File name: unweighted_events.lhe :-  Simulated high-energy proton-proton collisions ($p p \to Z \to b \bar{b}$) using MadGraph5_aMC@NLO (10,000 events).
2. File name: Z_boson.ipynb :- Reconstructed the mass of the Z boson by directly identifying which particles as b quarks using PDG ID's and then arranging them on the basis of highest transverse momentum.
3. File name: Z_boson_fastjet.ipynb :-  Reconstructed the $Z$ boson invariant mass using modern jet-clustering algorithms via FastJet (Anti-$k_t$).
4. File_name: Reconstruction.ipynb :- First step to improve the reconstruction for Z- jet jet by comparing with Z-bb at an event by event basis using the initial steps highlighted in the paper "Jet energy calibration with deep learning as a Kubeflow pipeline" by Daniel Holmberg, Dejan Golubovic and Henning Kirschenmann. Computed:
   
     $$y = \log \left( \frac{p_T^{\text{Z-bb}}}{p_T^{\text{Z-jet}}} \right)$$.

   In progress: Applying elementary regression models to the data that I have reconstructed and reading open data sets using Docker with the ultimate aim of learning how to use more advanced regression models and incorporating detector smearing into the data.
