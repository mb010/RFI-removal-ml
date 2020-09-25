# RFI-removal-ml
Machine learning to remove RFI from a response to a field of view of the EVLA in D-Configuration

Please make sure you have a ./data filepath available to store the simulated training data set.

The project is explained and presented in full in notebook_v4.ipynb. In it, I simulate a response signal from the EVLA, develop a system for adding RFI (noise) known to exist at the site, and then attempt to develop a model which can highlight and remove the noise - ideally without damaging the underlying signal.


### Limitations
The largest limitations include:
- Data simulation simplicity
- Data / feature engineering choices not optimised
- Suboptimal implementation of Random Forrest hyperparameters

This work serves as a proof of concept, it is not a final / commercial implementation (obviously).
