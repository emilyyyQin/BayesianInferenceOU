# BayesianInferenceOU
We experiment the bayesian method for estimating parameters on a bidimensional OU process.
The codes are written in Julia language using Jupyter Notebook.
## Preparations
Before doing the experiments, we need to import the packages from
"https://github.com/JuliaDiffusionBayes/ObservationSchemes.jl.git"
"https://github.com/JuliaDiffusionBayes/DiffusionDefinition.jl.git" and 
"https://github.com/JuliaDiffusionBayes/GuidedProposals.jl.git"
## Experiments
To evaluate the identifiability of parameters, run "Bayesian_inference_opt-identifiability".
To estimate the model parameters, run "Bayesian_inference_opt_param".
To perform joint estimation with reparametrization, run "Bayesian_inference_opt_joint_ratio" and "Bayesian_inference_opt_joint_sum".
To estimate the AIF, run "Bayesian_inference_AIF".
