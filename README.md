# GEW dispersion script [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7010603.svg)](https://doi.org/10.5281/zenodo.7010603)

**Script to compute guided waves in plates.** 

Extremely fast and robust computation of guided elastodynamic waves (GEWs) in plates. Select between Lamb waves, SH waves or coupled polarization. Easily computes the complex wavenumber dispersion curves. The script implements the spectral collocation method (SCM) based on DMSUITE.

![dispersion_fig](https://user-images.githubusercontent.com/3725269/185589376-c991b579-2550-40e8-8d7b-d90de9edec77.png)

Features:
- does not miss solutions, super fast 
- only ~50 lines of Matlab code
- general anisotropy
- possible to include dissipation
- Lamb/SH/coupled polarization
- complex wavenumbers

Code repository: [<img src="https://www.svgrepo.com/show/35001/github.svg" alt="GitHub" width="27px" />](https://github.com/dakiefer/gew_dispersion_script) [https://github.com/dakiefer/gew_dispersion_script](https://github.com/dakiefer/gew_dispersion_script)

Latest release: [![DOI](https://zenodo.org/badge/526614500.svg)](https://zenodo.org/badge/latestdoi/526614500)

For theory on guided waves and spectral collocation refer to:<br/>
D. A. Kiefer, _Elastodynamic quasi-guided waves for transit-time ultrasonic fladfow metering_, ser. FAU Forschungen, Reihe B, Medizin, Naturwissenschaft, Technik, vol. 42. Erlangen: FAU University Press, 2022, doi: [10.25593/978-3-96147-550-6](http://doi.org/10.25593/978-3-96147-550)

## How to use

1. Change into the `GEW_dispersion_script` folder or add it to the Matlab path.
2. Execute `plate_SCM.m` .
3. Enjoy!

## Dependencies

The author is grateful for permission to bundle `chebdif.m` from DMSUITE:

J.A.C Weideman (2022). DMSUITE (https://www.mathworks.com/matlabcentral/fileexchange/29-dmsuite), MATLAB Central File Exchange. Retrieved August 18, 2022.

## Author

Created 2022 by Daniel A. Kiefer while at Institut Langevin, ESPCI Paris.

If this code is useful to you, please cite it as:

> Kiefer, D. A. (2022). GEW dispersion script [Computer software]. https://doi.org/10.5281/zenodo.7010603

and if appropriate also

> D. A. Kiefer, _Elastodynamic quasi-guided waves for transit-time ultrasonic flow metering_, ser. FAU Forschungen, Reihe B, Medizin, Naturwissenschaft, Technik, vol. 42. Erlangen: FAU University Press, 2022, doi: [10.25593/978-3-96147-550-6](http://doi.org/10.25593/978-3-96147-550-6).

Contact: [daniel.kiefer@espci.fr](mailto:daniel.kiefer@espci.fr) &nbsp; ● &nbsp; [dakiefer.net](https://dakiefer.net) &nbsp; ● &nbsp; Follow me on [ResearchGate](https://www.researchgate.net/profile/Daniel-Kiefer-5)!

[<img src="https://user-images.githubusercontent.com/3725269/185571121-f5fcd518-32de-40b2-b4b1-f4ef0610ccd1.svg" alt="Logo Institut Langevin" width="250px" />](https://www.institut-langevin.espci.fr) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [<img src="https://user-images.githubusercontent.com/3725269/185570398-ca2796ab-2bd3-4171-a7a6-af1f74014504.svg" alt="Logo ESPCI Paris" width="260px" />](https://www.espci.psl.eu/en/)

