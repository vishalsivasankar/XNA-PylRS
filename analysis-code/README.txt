This subfolder contains the Python scripts used to analyze simulation trajectories and generate data for plots associated with the computational model.

1. bp_occupancy.py — Calculates the base-pair occupancy of tRNA stem regions using DSSR outputs from individual simulation frames. Generates a CSV file containing the occupancy values for each base pair in the stem regions.
2. interface-metrics.py — Quantifies the tRNA–PylRS interface by calculating the number of residues and atoms involved in intermolecular contacts. Generates a CSV file containing the frame-wise contact counts.
3. shape-met.py — Calculates the radius of gyration and relative shape anisotropy of the tRNA. Generates a CSV file containing the frame-wise values of both structural descriptors.
4. detect_dt_hbonds.py — Identifies and characterizes hydrogen bonds between the D- and T-loops of the tRNA. Generates multiple CSV files containing frame-wise hydrogen-bond counts, occupancy statistics, and information about the residues involved in hydrogen-bond formation.
5. calc_elbow.py — Calculates geometric parameters characterizing the tRNA elbow region. Generates a CSV file containing the frame-wise values of the geometric descriptors.
