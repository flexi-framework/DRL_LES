# DRL_LES
Accompanying Data for the Publication "*Deep Reinforcement Learning for Turbulence Modeling in Large Eddy Simulations*".

This repository contains all
- trained models and
- required simulation data

presented and used in said publication.

The training checkpoints in the `logs` folder for each configuration allow to restart the training and to evaluate the trained model.
Since all parameter files are the original files used for training, the number of used processors and parallel environments have to be decreased in order to run it on a local machine.
(The training took place on multiple compute nodes with 128 cores each).
Please see <https://github.com/flexi-framework/relexi> for more details and some example configurations to run Relexi on a local machine.
To modify the simulation environment (e.g. increase the simulation time) or to post-process the simulation data, please see <https://github.com/flexi-framework/flexi> or <https://www.flexi-project.org/doc/userguide/userguide.pdf> for more details.
