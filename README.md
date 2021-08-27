This repository contains Matlab codes for illustrative simulation results for the paper 'Information Design in Non-atomic Routing Games with Partial Participation: Computation and Structural Properties' by Yixian Zhu and Ketan Savla.

This version of project is distributed under the [MIT License].

To run the code, first download and extract the Information_Design_Simulations directory to your computer. Then add correct path to the main.m file on line 5 and both private_cost_compute_hpc.m and public_cost_compute_hpc.m file on line 7, 8, 9.

You may change the network topology and parameters of latency functions by changing the link-path relationship matrix 'M' and parameter matrix 'alpha' from params_1.mat file. For 'M' matrix, rows are links while columns are paths, elements of 'M' is 1 if certain path consists of certain link, and 0 otherwise.