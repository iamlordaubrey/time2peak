## Time 2 peak
A colormap representing the time to peak of each pixel

### To run
Ensure a version of conda has been installed locally. 
You can download either [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/distribution/).

#### Using jupyter notebook
Start the notebook server. 
- Open a terminal
- Navigate to the project root folder and run: 
```.env
jupyter notebook
```
- Click on the cell menu and select `Run All`

#### Using an IDE
Open project in IDE. Ensure you're at the project's root folder. Run:
 
```.env
conda env create --file environment.yaml
```

This creates the environment and installs required packages. If prompted with a y/n question, enter `y`.

To activate the environment, run:
```.env
conda activate time2peak_env
```

Run the code, using the equivalent of `Run All` in your IDE.