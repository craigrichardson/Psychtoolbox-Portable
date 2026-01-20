Psychtoolbox-Portable

Psychtoolbox does not have to be "installed" according to the default instructions at http://psychtoolbox.org/

The default instructions make some significant assumptions about the type of installation and requiment of administrative privledges, neither of which are required on a properly configured system.

Experimenters are expected to download and bundle the Psychtoolbox installation *they* wish to use in a directory with their experiment and whatever stimuli and other resources are required.

MyExperimentDir\
- run_my_experiment.m
- my_experiment.m
- my_experiment_resources\
- Psychtoolbox\

They can then use this script to configure Psychtoolbox and launch their experiment or otherwise modify the code and embed it in their own experiment.
Psychtoolbox can be downloaded at https://github.com/Psychtoolbox-3/Psychtoolbox-3/releases
In the downloaded .zip file you only need to extract the Psychtoolbox\ folder.

Thus the whole MyExperimentDir fully contains the experiment including Psychtoolbox and should be portable between different Behavioural computers.

This also allows for different experiments to easily use different versions of Psychtoolbox.