[![Build Status](https://app.travis-ci.com/IEAWindTask37/IEA-3.4-130-RWT.svg?branch=master)](https://travis-ci.com/IEAWindTask37/IEA-3.4-130-RWT)

# IEA-3.4-130-RWT
This repository contains the model data of the onshore reference wind turbine developed within IEA Wind Task 37. 

The documentation of the turbine and the design process is accessible here: https://www.nrel.gov/docs/fy19osti/73492.pdf

The data include the OpenFAST aeroelastic files, a .yaml file with the corresponding json schema and open-source controllers.

The documentation of the .yaml file is available at https://windio.readthedocs.io/en/latest/

The OpenFAST model is up to date with release 3.5.0 and uses the ROSCO controller https://github.com/NREL/ROSCO release v2.7.0

If you use the wind turbine, please cite it like this:

	@techreport{RWT,
	Author = {Pietro Bortolotti and Helena Canet Tarres and Katherine Dykes and Karl Merz and Latha Sethuraman and David Verelst and Frederik Zahle},
	Howpublished = {NREL/TP-73492},
	Institution = {International Energy Agency},
	Title = {IEA Wind Task 37 on Systems Engineering in Wind Energy -- WP2.1 Reference Wind Turbines},
    Url ={https://www.nrel.gov/docs/fy19osti/73492.pdf},
	Year = {2019}}

For questions, please ask to Pietro Bortolotti (pietro.bortolotti@nrel.gov)