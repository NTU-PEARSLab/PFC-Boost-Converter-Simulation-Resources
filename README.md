# PFC-Boost-Converter-Simulation-Resources
These are resources for the article “Simulation Technique and Mathematical Basis for Faster AC Analysis of Power Factor Correction Boost Converters” by Katherine A. Kim and Thomas G. Wilson Jr., published in IEEE Access.

SIMPLIS File Download
These files output the AC analysis (frequency response) for the control loop, input impedance, and output impedance of a PFC boost converter. Simulations are provided for both an AC voltage source and a DC voltage source to the PFC boost converter. The DC voltage source simulates much faster and gives almost the same results as the AC source for the control loop and output impedance measurements, but not the input impedance. In short, the DC source should NOT be used to measure input impedance , but the file is provided here as a reference. Files are ready to run.

Zip File: SIMPLIS_ControlLoop_Zin_Zout_20240403
Contains:
Control Loop with AC Source: ControlLoop_AC_KimLin_20240403.sxsch
Control Loop with DC Source: ControlLoop_DC_KimLin_20240403.sxsch
Input Impedance with AC Source: Zin_AC_KimLin_20240403.sxsch
Input Impedance with DC Source: Zin_DC_KimLin_20240403.sxsch
Output Impedance with AC Source: Zout_AC_KimLin_20240403.sxsch
Output Impedance with DC Source: Zout_DC_KimLin_20240403.sxsch

Matlab Figure File Download
These are the Matlab Figure files for the generated graphs used in the paper. Please refer to the paper for the descriptions. Six Matlab .fig files are included in the .zip file below.

Zip File: Matlab_Figure_Files_20240408
Contains:
Figure2.fig
Figure3.fig
Figure4.fig
Figure7.fig
Figure9.fig
Figure12.fig
