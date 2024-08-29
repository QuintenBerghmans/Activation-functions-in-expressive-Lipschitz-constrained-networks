# Activation-functions-in-expressive-Lipschitz-constrained-networks
This repository contains the code that was used for my (Quinten Berghmans) Master's thesis on "On the effect of the activation function on the adversarial robustness of neural networks".

Four files can be found: 
- "Optuna_point_classifier_optimiser.ipynb" was used to perform the optimisation of the hyperparameters, for a basic 2d case with no noise
- "Basic_fully_connected_network_Point_classifier_with_different_activation_functions.ipynb" was used to perform the experiments that do not make use of the expressive Lipschitz-constrained architecture, for all 2D/4D, noisy/noiseless, circle/square tests. Both Multiclass hinge loss and Cross entropy are used.
- "Expressive_Lipschitz_constrained_network_for_point_classifier_with_different_activation_functions.ipynb" is used for all experiments with the expressive Lipschitz-constrained architecture.
- "plot_the_activation_functions" is used for the visualization of the activation functions.

The files are constructed in such a way that by adjusting the parameters/constants at the top, the desired experiments are run.
