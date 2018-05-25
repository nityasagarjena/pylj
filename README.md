<img src="https://github.com/arm61/pylj/blob/master/logo/logo.png?raw=true" style="width: 80%;"/>

### what is pylj?

pylj is an open-source library to facilitate student interaction with classical simulation. It is designed to operate within the Jupyter notebook framework, making it easy to implement in the classroom, or computer lab. Additionally, due to the open-source, and documented, nature of the code it is easy for educators to add unique, custom extensions.

### what does pylj offer?

Currently pylj will perform the simulation of a 2D argon system by molecular dynamics, with both NVE and NVT ensembles available and making use of a Velocity-Verlet integrator. A series of sampling classes exist (found in the sample module), such as the Interactions and Scattering classes. However, it is straightforward to build a custom sampling class either from scratch or using the sampling class building tools.

### example exercises

We are currently in the process of developing example laboratory exercises that make use of pylj. These will include a study of ideal and non-ideal gas conditions and the effect of the phase transitions on the radial distribution function, scattering profiles and mean squared deviation. Currently Andrew's interactive lecture on molecular dynamics for neutron scattering is available [here](http://pythoninchemistry.org/introduction-to-md-ntc).

### how to get pylj?

If you are interested in using pylj, in any sense, fork the code at [github.com/arm61/pylj](http://www.github.com/arm61/pylj) or email Andrew (arm61 ‘at’ bath.ac.uk). We are currently investigating the feasibility of hosting a freely available test instance on Amazon Web Services. Full API level documentation is available at [pylj.rtfd.io](http://pylj.rtfd.io).

### requirements

To run pylj locally we recommend installing the [anaconda](http://pythoninchemistry.org/running-jupyter-locally), which gives access to Jupyter notebook framework and the necessary packages. It is also it is necessary to have a C++ compiler, most macOS or Linux machines should already have this, on Windows it is best to install the [Visual C++ package](https://www.microsoft.com/en-gb/download/details.aspx?id=48145). 

### how to cite pylj 

Thank you for using pylj. If you use this code in a teaching laboratory or a publication we would greatly appreciate if you would use the following citation. Andrew R. McCluskey, Benjamin J. Morgan, Karen J. Edler, Stephen C. Parker (2018). pylj, version 0.0.6a. Released: 2018-05-15, DOI: 10.5281/zenodo.1212792.

<p><a href="https://zenodo.org/badge/latestdoi/119863480"><img src="https://zenodo.org/badge/119863480.svg" alt="DOI"></a><a href='http://pylj.readthedocs.io/en/latest/?badge=latest'><img src='https://readthedocs.org/projects/pylj/badge/?version=latest' alt='Documentation Status' /></a></p>

