%=========================================================
startup.m:
must be called at start-up time to set the path

README.txt: this file

Directories with top-level execution scripts and examples.
ch_analysis:
	scripts for plots of V_m over uA/cm^2 and mS/cm^2
		gen_i_vm_001a.m
		gen_i_vm_001e.m
gain_filter:
	scripts to produce a gain plot (firing frequency over strength 
	of input) for various neuron types and parameters
		gf_001.m
		gf_002.m
		gf_002_inh.m
		gf_002_sk.m
		gf_002a_sk.m
		gf_002b_sk.m
		gf_002c_sk.m
		gf_002d_sk.m
		gf_002e_ie.m
		gf_002e_sk.m
		gf_003.m

input_analysis:
	scripts to plot various types of inputs
	for demonstration

interactive:
	This directory contains a number of scripts to initialize the sim,
	to generate inputs, produce plots and save the results.
	These scripts can be used in an interactive mode.
	Two examples of simple scripts are given:
		ex_001.m:   runs 5 variable neurons on generated input 
				and produces plots
		ex_izh_001.n:  runs 4 2D neurons

Directories with implementation code and utility functions
analysis:
	various routines to generate plots of simulation results

gui:
	draft of a gui for parameter exploration (not finished; used
	simulated synaptic input only and only 4 \mu parameters can be changed

input:
	utilities to generate different kinds of input signals
	(poisson-distributed EPSPs, IPSPs, single spikes, sin, DC, etc.)

neuron:
	contains definitions of the ion channels execution (simulation)
	mechanisms for one neuron or a vector of neurons

syn_response:
	contains main simulator functionality; run_sr4 called from various
	other directories

