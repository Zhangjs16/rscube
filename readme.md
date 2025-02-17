# RSCube 

These general tutorials are meant to concisely demonstrate how to apply numerical and GIS python to analyze SAR and other remotely sensed data for basic environmental monitoring and land use classification.
We have some simple functions which we include under `rscube`, though they are basic wrappers around the powerful GIS libraries `rasterio`, `geopandas`, etc.

# Installation

1. Download the repository.
2. Open the [terminal](https://support.apple.com/guide/terminal/welcome/mac).
3. Change the working directory of the terminal session to the downloaded repository.
4. Create a virtual environment using conda via: 

	`conda create --name rscube python=3.7 --yes`
	
	Make sure to hit `y` to confirm that the listed packages can be downloaded for this environment.

5. Activate the virtual environment: 

	`conda activate rscube`.

6. Install requirements with pip: 

	`pip install -r requirements.txt`

	or with conda:

	`conda install -c conda-forge --yes --file requirements.txt`

7. Install `rscube` into the environment:
   
   `pip install .`

8. Create a new jupyter kernel: 

	`python -m ipykernel install --user --name rscube`.

# License

See [LICENSE.txt](LICENSE.txt).

>Copyright 2020, by the California Institute of Technology. ALL RIGHTS RESERVED. United States Government Sponsorship acknowledged. Any commercial use must be negotiated with the Office of Technology Transfer at the California Institute of Technology.

>This software may be subject to U.S. export control laws. By accepting this software, the user agrees to comply with all applicable U.S. export laws and regulations. User has the responsibility to obtain export licenses, or other export authority as may be required before exporting such information to foreign countries or providing access to foreign persons.