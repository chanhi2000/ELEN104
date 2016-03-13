# lab03

## TITLE:
Introduction to Transmission Lines

## INSTRUCTIONS:
1. This experiment is composed of 3 parts each containing:
	1. Simulations with Agilent Advanced Design System (ADS)
	2. Calculations and/or discussions
2. The students *should work in group of two* and *submit one lab report per group*.
3. Make sure to save your project files at each step before moving to the next part and print (to `.pdf` or save as `.jpg`, `.png`, etc) your simulation results. After finishing your lab and printing all the needed results for the report, delete the projects on the computer you have been using.
4. The students will get back their marked lab reports from the TA in the lab/tutorial sessions one week after they handed in the report.

## 1: ADS SIMULATIONS OF A BASIC TRANSMISSION LINE CIRCUIT
#### INTRODUCTION:
Transmission Lines (TL) are used to provide connectivity between a source and a load. This definition applies to a wide range of interconnects from power lines to conductor traces on printed circuit boards. The main characteristic that can be attributed to a transmission line in comparison with wires used for DC connectivity is *the delay*.


#### OBJECTIVE:
In this experiment, you will investigate the concept of delay in a simple transmission line circuit using transient simulations.


#### PROCEDURE(1):
First, review your ADS tutorial slide on how to build a circuit and run simulations to get started and build the following circuit schematic window of ADS;
1. From the selection box on the toolbar select “Simulation-Transient”, and from the respective palette insert a “Transient/Convolution Simulation”.
2. Double click on the transient simulation menu and change the “stop time” to $$3\:\mu\text{s}$$ and the “step” to $$100\:\text{ns}$$. Leave other parameters as default.
3. From the selection box on the toolbar select “Sources-Time Domain”, and from the respective palette select `VtSine`.
4. By double clicking on the source you can set its parameters’ values. In this simulation, use the default values of 0 for `Vdc`, `Delay`, `damping` and `phase` but set `Amp=1V`, and `f=1MHz`.
5. Add a source resistance (resistance in series with the source): $$R_S=50\:\Omega$$.
6. Add a load resistance of $$Z_L=50\:\Omega$$.
7. To connect the source and load we need to add connectivity wires. Just for the sake of representation of a zero resistance wire, here we add a resistor $$R_\text{wire}=0\:\Omega$$ between $$R_S$$ and $$Z_L$$. Note in building other circuits we do not add this representation of zero resistance wire.
8. Connect the nodes using simple connectivity wires (Choose `Insert Wire` from the toolbar).
9. Add the ground connections for the source and load.
10. Assign node labels using “Insert Wire/Pin Label” to input (after $$R_S$$) as `Vin`, and to
output (across $$Z_L$$, on the end that is not connected to ground) `Vout`.
11. Press `F7` or click on simulation button to run simulations.
12. In the output window, select the “Rectangular Plot” from the palette at the right of
this new window, in the appearing window select “`Vin`” or “`Vout`” and click “`Add`”.
13. After clicking `OK`, the output is drawn versus time.


#### REPORT AND DISCUSSION:
1. Plot the voltage waveforms, `Vin` and `Vout`.
2. Do you see any difference between `Vin` and `Vout`? Is Vout delayed in comparison with `Vin`?

**NOTE**: *Remember to save/(print to `.pdf` file) the output plots and the schematic of the circuit for your report.*


#### PROCEDURE(2):
1. Use the same set-up as PROCEDURE(1) for Simulation engine and source.
2. Choose an ideal transmission line component (TLIN from “TLines-Ideal” Palette in the Schematic Window), with the “characteristic impedance” of Z0 =50 Ω and the “electrical length” of E= π and “reference frequency for electrical length”
same as the frequency of the source in Step 1, f=1 MHz.
3. Insert the transmission line between the load and source and add the needed
wiring connections.
4. Assign Vin node after RS and Vout at ZL (same as Step 1).
5. Press F7 or click on simulation button to run simulations.
6. Create output plots as described in Step 1


#### REPORT AND DISCUSSION:
1. Plot the voltage waveforms, `Vin` and `Vout`.
2. Do you see any difference between Vin and Vout? Is Vout delayed in comparison with `Vin`? Measure the delay.

**NOTE**: *Remember to save/(print to `.pdf` file) the output plots and the schematic of the circuit for your report.*





