Code for Perceptual and Value experiments analysis are presented here:
The folders for both experiments are structured in a similar way.

-----

1. <b>'analysis'</b>: results from the behavioural analysis.  
	<i>ResultsBehavioural</i>: analysis for logistic choice models (Figure 1), gaze distribution (Figure 2) and behavioural measures comparison.  
	<i>FixationsAnalysis</i>: last fixation to chosen item analysis (Figure 3).  
	<i>FixAnalysis_GazeInTime</i>: gaze preference in time (Figure 3).  
	<i>RegressionModels</i>: hierarchical regression models for choice and confidence (Figures 2 and 4).  
	<i>SupplementaryModels</i>: hierarchical regression model comparison for choice and confidence.  


2. 'glamModels'</b>: estimation and results from GLAM model analysis.

	<i>GLAM_individual_...</i> : model parameter estimation for like and dislike (frame-evidence* and preference-evidence) in Value Experiment. In Perceptual Experiment most and fewest(frame-evidence and default-evidence). Separate scripts for each frame estimation.  
	<i>Individual_Simulations_BalanceEvidence</i>: balance of evidence simulations, with and without gaze influence.  
	<i>Out_of_sample_comparison</i>: individual out-of-sample comparison test set vs GLAM predicted (Figure 5).  
	<i>BE_ExtraFigs_SumVal</i>: generation of figures for balance of evidence simulations (Figure 6).  
	<i>ParamsCompare</i>: comparison of GLAM parameters between frames.  
	<i>ModelComparison</i>: WAIC score comparison for frame-evidence and preference-evidence models.  

    2.1 Additional folder <b>'glamModels/results'</b> contains output files from GLAM estimations plus our balance of evidence simulations:

      <i>glamModels/results/estimates</i>: contains GLAM estimation parameters.  
      <i>glamModels/results/predictions</i>: contains simulated trials using GLAM parameters for each participant.  
      <i>glamModels/results/preprocessed</i>: contains test sets for out-of-sample comparison.  
      <i>glamModels/results/simulations_evidence</i>: contains balance of evidence simulations datasets.  
      <i>glamModels/results/waic</i>: contains WAIC scores for each model and participant.  


-----

*Inv: (inverted) refers to frame relevant evidence (value or number of dots) used for model estimation/results. This notation is used in some files and variable anmes in the GLAM model scripts.  
** In the Perceptual Experiment scripts use More and Less to refer to labels Most and Fewest, respectively, used in the manuscript.
