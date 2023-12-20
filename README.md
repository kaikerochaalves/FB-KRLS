# FB-KRLS (fixed-budget kernel recursive least squares)

The fixed-budget kernel recursive least squares (FB-KRLS) is a model proposed by Vaerenbergh et al. [1].

- [FB-KRLS](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/Model/FB_KRLS.py) is the FB-KRLS model.

- [GridSearch_AllDatasets](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/GridSearch_AllDatasets.py) is the file to perform a grid search for all datasets and store the best hyper-parameters.

- [Runtime_AllDatasets](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/Runtime_AllDatasets.py) perform 30 simulations for each dataset and compute the mean runtime and the standard deviation.

- [MackeyGlass](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/MackeyGlass.py) is the script to prepare the Mackey-Glass time series, perform simulations, compute the results and plot the graphics. 

- [Nonlinear](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/Nonlinear.py) is the script to prepare the nonlinear dynamic system identification time series, perform simulations, compute the results and plot the graphics.

- [LorenzAttractor](https://github.com/kaikerochaalves/FB-KRLS/blob/b5ec4fbea31fc2fda2c36ac46a0020d19807d1c7/LorenzAttractor.py) is the script to prepare the Lorenz Attractor time series, perform simulations, compute the results and plot the graphics. 

[1] S. Van Vaerenbergh, I. Santamar ́ıa, W. Liu, J. C. Pr ́ıncipe, Fixed-budget kernel recursive least-squares, in: 2010 IEEE International Conference on Acoustics, Speech and Signal Processing, IEEE, 2010, pp. 1882–1885. 
doi: https://doi.org/10.1109/ICASSP.2010.5495350
