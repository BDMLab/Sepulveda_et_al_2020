Code for Perceptual and Value experiments analysis are presented here:
The folders for both experiments are structured in a similar way.

-----

1. Analysis: results from the behavioural analysis
	ResultsBehavioural: analysis for logistic choice models (Figure 1), gaze distribution (Figure 2) and behavioural measures comparison.
	FixationsAnalysis: last fixation to chosen item analysis (Figure 3)
	RegressionModels: hierarchical regression models for choice and confidence (Figures 2 and 4)

	SupplementaryModels: hierarchical regression model comparison for choice and confidence.


2. glamModels: estimation and results from GLAM model analysis.

	GLAM_individual_... : model parameter estimation for like and dislike (frame-evidence* and preference-evidence) in Value Experiment. In Perceptual Experiment most and fewest(frame-evidence and default-evidence). Separate scripts for each frame estimation.
	Individual_Simulations_BalanceEvidence: balance of evidence simulations, with and without gaze influence.
	Out_of_sample_comparison: individual out-of-sample comparison test set vs GLAM predicted (Figure 5).
	BE_ExtraFigs_SumVal: generation of figures for balance of evidence simulations (Figure 6).
	ParamsCompare: comparison of GLAM parameters between frames.
	ModelComparison: WAIC score comparison for frame-evidence and preference-evidence models

2.1 Additional folder "glamModels/results" contains output files from GLAM estimations plus our balance of evidence simulations:

glamModels/results/estimates: contains GLAM estimation parameters.
glamModels/results/predictions: contains simulated trials using GLAM parameters for each participant.
glamModels/results/preprocessed: contains test sets for out-of-sample comparison
glamModels/results/simulations_evidence: contains balance of evidence simulations datasets
glamModels/results/waic: contains WAIC scores for each model and participant


-----

*Inv: (inverted) refers to frame relevant evidence (value or number of dots) used for model estimation/results. This notation is used in some file names and variable in the scripts.

** In the perceptual experiment scripts More/Less has been used to name some files and variables. These are equivalent to the labels Most/Fewest used to indicate the frames, respectively. 
