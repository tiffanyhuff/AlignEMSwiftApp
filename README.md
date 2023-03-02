Description:
-----------------------

This application will allow a user to submit a job on the [Texas Advanced Computing Center (TACC)](https://www.tacc.utexas.edu/) [Lonestar6 Supercomputer](https://www.tacc.utexas.edu/systems/lonestar6) to utilize [AlignEM-SWiFT](https://github.com/mcellteam/swift-ir); an implementation of SWiFT-IR (Signal Whitening Fourier Transform Image Registration), developed by Art Wetzel, Tom Bartol, and Bob Kuczewski.

Running the Application:
-----------------------
To run the application, the user must submit a job using the [3D Electron Microscopy (3Dem)](https://3dem.org/) web-based research platform. Once running, a virtual DCV session will be initialized for the user, and a button on the History/Jobs page will appear allowing the user to open the session. Additionally, a document titled 'alignem_dcvserver.txt' will be created in the user's work folder with connection instructions. Once connected, the AlignEM-SWiFT software will begin running.

For instructions on using AlignEM-SWiFT, please see the [documentation](https://github.com/mcellteam/swift-ir/blob/development_ng/docs/tacc/README.md). Additional information can be found [here](https://wikis.utexas.edu/display/khlab/tSEM+image+alignment+using+AlignEM-SWiFT).

 Acknowledgements:
---------------------

AlignEM-SWiFT was originally written by Patrick Parker in Aug. 2020, with contributions from Mahija Ginjuaplli, Dusten Hubbard, Masa Kuwajima, and Edwin Vargas-Garzon.

[Arthur W. Wetzel, Jennifer Bakal, Markus Dittrich, David G. C. Hildebrand, Josh L. Morgan, Jeff W. Lichtman (2016) Registering large volume serial-section electron microscopy image sets for neural circuit reconstruction using FFT signal whitening.](https://arxiv.org/abs/1612.04787)
